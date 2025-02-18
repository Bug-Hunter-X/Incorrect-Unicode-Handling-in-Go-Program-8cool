# Incorrect Unicode Handling in Go Program

This repository demonstrates a common error in Go programs related to Unicode handling. The `main` function attempts to print a string containing Unicode characters.  On systems that don't properly support UTF-8 encoding, this can lead to unexpected output or errors. The solution showcases the proper way to handle Unicode strings in Go to ensure consistent output across different systems.

## Bug

The `bug.go` file contains the buggy code which uses UTF-8 encoding. However, the output may be garbled if your terminal is not configured to handle UTF-8.

## Solution

The `bugSolution.go` demonstrates the fix for the bug.

## How to run

1. Clone this repo
2. Navigate to this directory
3. Run the program using `go run bug.go` and `go run bugSolution.go`