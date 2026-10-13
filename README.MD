# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

# Calculation of grades

This grade calculator supports three categories:
  - Assignments: worth 50%
  - Exams: worth 35%
  - Essays: worth 15%

grade = 0.5 * assignment average + 0.35 * exam average + 0.15 * essay average

# Requirements

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
