racket-package
==============

This is a template repository for GitHub that guides you through creating a new package using github and the `raco pkg new` command.

Steps: 
1. go to the the repo homepage and click the green `Use this template` button
2. make a local copy of the template on your PC
3. set your PATH environment variable to the racket/bin
4. open command prompt
5. type `raco pkg new your-package-name-name-here`

`raco pkg new` generates
- license files 
- Racket `.gitignore`
- main.rkt
- scribble files



**tasks**
- [ ] update this file [`README.md`](README.md)
- [ ] update [`.travis.yml`](.travis.yml) 
- [ ] update licence files [`LICENSE-MIT`](LICENSE-MIT) and [`LICENSE-APACHE`](LICENSE-APACHE) with name and year, or change to your desired licence.      
- [ ] update [`info.rkt`](info.rkt)
- [ ] update [`scribblings/racket-package.scrbl`](scribblings/racket-package.scrbl)
- [ ] update [`main.rkt`](main.rkt) to get coding.

For more details see [_Tutorial: Creating a Package_](https://blog.racket-lang.org/2017/10/tutorial-creating-a-package.html)


To install (from within the package directory):
`$ raco pkg install`
To install (once uploaded to pkgs.racket-lang.org):
`$ raco pkg install <<name>>`
To uninstall:
`$ raco pkg remove <<name>>`
;; To view documentation:
`$ raco docs <<name>>`

See the current version of the racket style guide here:
<http://docs.racket-lang.org/style/index.html>
