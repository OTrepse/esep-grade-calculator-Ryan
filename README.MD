# ESEP Grade Calculator

Go library for computing final course grade for assignments, exams, and essays.

Runtime requirements:
Golang 1.24+

# files
`go.mod`: Go module name and required Go version.
`grade_calculator.go`: calculator, grade types, weighted-average logic, and letter-grade conversion.
`grade_calculator_test.go`: unit tests for calculator behavior.

Run unit tests:
```
cd grade_calculator/
go test -v
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```