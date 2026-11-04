# gopal-sample-gh-action
The repository demonstrates the sample github action developed as an excercise.

## Usage
```yaml
- uses: actions/checkout@v4
- uses: charyulu/gopal-sample-gh-action@main
```
Publishes the repository name, branch, committing user and commit date/time to the log and job summary, and exposes them as outputs `repository`, `branch`, `user` and `datetime`.
