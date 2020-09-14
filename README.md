@awesome-crowdin/contributors
========================

A CLI for automating the maintenance of your contributors table ✨

Automate acknowledging translators to your open source projects

<!-- toc -->
* [Usage](#usage)
* [Flags](#flags)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @awesome-crowdin/contributors

$ crowdin-contributors
Downloading report...... ⢿

$ crowdin-contributors --help
crowdin-contributors --help
USAGE
  $ crowdin-contributors

OPTIONS
  -c, --contributorsPerLine=contributorsPerLine          [default: 7]
...
```
<!-- usagestop -->
# Flags
  -c, --contributorsPerLine=contributorsPerLine          [default: 7]
  -f, --file=file                                        [default: README.md] File name to write results to

  -f, --placeholder=placeholder                          [default: <!-- CROWDIN-TRANSLATORS -->] Placeholder to look for and replace 
                                                         in the -f

  -h, --help                                             show CLI help

  -m, --maxContributors=maxContributors                  [default: 30] Only -m contributors will be shown

  -m, --mimimumWordsContributed=mimimumWordsContributed  Minimum words contributed (both translated and approved)

  -o, --organization=organization                        Crowdin Organization (for Crowdin Enterprise only, leave empty for 
                                                         crowdin.com)

  -p, --project=project                                  Crowdin project ID (number)

  -t, --token=token                                      Crowdin Token

  -v, --version                                          show CLI version
<!-- flags -->

<!-- commandsstop -->
