# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Key Features:
- Define different category weights for each type of assignment (Assignment, Exam, Essay)
- Log student's grades on each assignment in the gradebook
- Calculate a final course score using a weighted average for each category
- Translate the final course score to a letter grade based on specified grade boundaries

Runtime requirements:
Golang 1.24+

To install Golang (MacOS):
```
brew install go
```

To check Golang version:
```
go version
```

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