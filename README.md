# Simple Interest Calculator

A small Bash script that calculates simple interest, used to practise an open-source Git workflow: forking, branching, pull requests, and community files (licence, code of conduct, contributing guide). It comes from a scenario where a micro-finance start-up moves its tooling from SVN to Git to build financial tools for low-income customers.

![Shell](https://img.shields.io/badge/shell-bash-4eaa25)
![License](https://img.shields.io/badge/license-Apache%202.0-blue)

## Formula

```
simple interest = principal × rate × time / 100
```

| Input | Meaning |
| --- | --- |
| Principal | Amount borrowed or invested |
| Rate | Annual interest rate, in percent |
| Time | Period in years |

## Usage

```bash
git clone https://github.com/albertmwangwa/github-final-project.git
cd github-final-project
chmod +x simple-interest.sh
./simple-interest.sh
```

```
Enter the principal:
1000000
Enter rate of interest per year:
12
Enter time period in years:
2
The simple interest is:
240000.00
```

Requires `bash` and `bc`.

## Repository practices

- [`LICENSE`](LICENSE): Apache 2.0
- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md): community standards
- [`CONTRIBUTING.md`](CONTRIBUTING.md): how to propose changes through pull requests

## Credits

Original script by Upkar Lidder (IBM), from the *Getting Started with Git and GitHub* course. Maintained in this fork by [Albert William Mwangwa](https://github.com/albertmwangwa).

The script is a learning sample, not production financial software.
