# Actix-Web with Casbin-RS

Just a demo for actix-web & casbin.

## Usage

```shell
git clone git@github.com:PsiACE/actix-casbin-example.git
# or https://github.com/PsiACE/actix-casbin-example.git
cd actix-casbin-example
cargo run
```

In this example, you can get the the successful result at `http://localhost:8080/success` (accessible) and the failed result at `http://localhost:8080/fail` (inaccessible, `ERR_EMPTY_RESPONSE`).

## Contact

Chojan Shang - [@PsiACE](https://github.com/psiace) - <psiace@outlook.com>

Project Link: [https://github.com/psiace/actix-casbin-example](https://github.com/psiace/actix-casbin-example)

## License

Licensed under either of:

- Apache License, Version 2.0 ([LICENSE-APACHE](./LICENSE-APACHE) or [http://apache.org/licenses/LICENSE-2.0](http://apache.org/licenses/LICENSE-2.0))
- MIT license ([LICENSE-MIT](./LICENSE-MIT) or [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT))

## Credits

- [actix-web](https://github.com/actix/actix-web) - A small, pragmatic, and extremely fast rust web framework.
- [casbin-rs](https://github.com/casbin/casbin-rs)- An authorization library that supports access control models like ACL, RBAC, ABAC in Rust.
- [@xcaptain](https://github.com/xcaptain/)'s gist [example](gist.github.com/xcaptain/19ee94b330e2dbb0ed8798d836d5e48b) - Early work for example.
