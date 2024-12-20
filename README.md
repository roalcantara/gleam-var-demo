# gleam-var-demo

[![test](https://github.com/roalcantara/gleam-var-demo/actions/workflows/test.yml/badge.svg)](https://github.com/roalcantara/gleam-var-demo/actions/workflows/test.yml)

A simple glem demo app

[![MIT license](https://img.shields.io/badge/License-MIT-brightgreen.svg?style=flat-square)](LICENSE) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg?style=flat-square)][2] [![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)][4] [![Editor Config](https://img.shields.io/badge/Editor%20Config-1.0.1-crimson.svg?style=flat-square)][3] [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?logo=conventional-commits&style=flat-square)][10] [![Gleam](https://img.shields.io/badge/Gleam-0.15.0-ff69b4.svg?logo=gleam&style=flat-square)][11]

## Install

`git clone https://github.com/roalcantara/gleam-var-demo`

### Dependencies

- [git][5]
- [ASDF][6]
- [Divenv][7]
- [pre-commit][8]
- [gitlint][9]
- [gleam][11]

## Development

This [guide][12] shows you how to create and develop a [Gleam][11] project.

```bash
# setup
gleam new vars              # create the project
cd vars                     # navigate into the project directory

# develop
gleam run                   # run the project
gleam test                  # run the tests
gleam add envoy argv        # add the envoy argv dependencies
gleam add --dev gleescript  # add the gleescript dev dependency

# build
gleam build                 # build the project
gleam run -m gleescript     # compile the program to an escript

# run
./vars get USER             # run the program
```

## Acknowledgements

- [Standard Readme][4]
- [Conventional Commits][10]
- [Writing Gleam | Learn to work with Gleam projects][12]

## Contributing

- Bug reports and pull requests are welcome on [GitHub][0]
- Do follow [Editor Config][3] rules.
- Everyone interacting in the project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [Contributor Covenant][2] code of conduct.

## License

The project is available as open source under the terms of the [MIT][1] [License](LICENSE)

[0]: [https://github.com/roalcantara/gleam-var-demo] 'A simple glem demo app'
[1]: [https://opensource.org/licenses/MIT] 'Open Source Initiative'
[2]: [https://contributor-covenant.org] 'A Code of Conduct for Open Source Communities'
[3]: [https://editorconfig.org] 'EditorConfig'
[4]: [https://github.com/RichardLitt/standard-readme] 'Standard Readme'
[5]: [https://git-scm.com] 'Git'
[6]: [https://asdf-vm.com] 'ASDF'
[7]: [https://direnv.net] 'Direnv'
[8]: [https://pre-commit.com] 'A framework for managing and maintaining multi-language pre-commit hooks'
[9]: [https://jorisroovers.com/gitlint] 'git commit message linter'
[10]: [https://conventionalcommits.org] 'Conventional Commits'
[11]: [https://glem.dev] 'Gleam is a friendly language for building type-safe systems that scale!'
[12]: [https://gleam.run/writing-gleam] 'Writing Gleam | Learn to work with Gleam projects'
