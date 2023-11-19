# FetchAll

Fetchall fetches URLs in parallel and reports their times and sizes.

These are exercises 1.10, and 1.11 from the book The Go Programming Language by Brian W. Kernighan and Alan Donovan.

## Requirements

Make sure you have at least Go 1.21.4 installed on your system before running the program.

## How to Run

To run the Fetchall program, use the following command:

```bash
go run fetchall.go [URL1] [URL2] [URL3] ...
```

## Example Usage

```bash
go run fetchall.go https://go.dev/ https://gobyexample.com/ https://github.com/
```

## Example Output

After running the program, you should see output similar to the following:

```console
0.10s     6362  https://gobyexample.com/
0.14s   203168  https://github.com/
0.41s    61870  https://go.dev/
0.41s elapsed
```
