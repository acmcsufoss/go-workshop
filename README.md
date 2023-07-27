# go-workshop

Go workshop for ACM at CSUF.

The slides' source code is in [`acm-go.slide`](acm-go.slide). To view the
slides, head to [goworkshop.libdb.so](https://goworkshop.libdb.so).

The bookstore example is in [`cmd/bookstore`](cmd/bookstore). It contains a
full backend implementation with a REST API and a SQLite database. There's also
a small frontend in the `index.html` file.

## Development

To run the slides locally, you need to install [Go](https://golang.org/) and run the [`present`](https://godoc.org/golang.org/x/tools/present) tool:

```sh
go run golang.org/x/tools/cmd/present
```

---

7th weekly workshop (July 28th, 2023) of [Hot Open Source Software Summer hackathon](https://acmcsuf.com/hot) series hosted by [ACM CSUF Student Chapter](https://acmcsuf.com)'s [Open Source Software team](https://oss.acmcsuf.com/).
