# rustlings 🦀❤️

These are my solutions for the ![rustlings](https://github.com/rust-lang/rustlings) exercises as an intro
to the Rust language.

## Getting started

```bash
yay -Ss rust python3 # install cargo and python
cargo install --path # setup rustlings./install.sh
```

Then run `rustlings` from the terminal to check the exercises.

## Doing exercises

Go to `rustlings/exercises/<topic>`. A description for each topic is on the README.

```bash
rustlings watch
```

This will try to verify the completion of every exercise in a predetermined order (what we think is best for newcomers). It will also rerun automatically every time you change a file in the `exercises/` directory. If you want to only run it once, you can use:

```bash
rustlings verify
```

This will do the same as watch, but it'll quit after running.

In case you want to go by your own order, or want to only verify a single exercise, you can run:

```bash
rustlings run myExercise1
```

Or simply use the following command to run the next unsolved exercise in the course:

```bash
rustlings run next
```

In case you get stuck, you can run the following command to get a hint for your
exercise:

```bash
rustlings hint myExercise1
```

You can also get the hint for the next unsolved exercise with the following command:

```bash
rustlings hint next
```

To check your progress, you can run the following command:

```bash
rustlings list
```

## Testing yourself

After every couple of sections, there will be a quiz that'll test your knowledge on a bunch of sections at once. These quizzes are found in `exercises/quizN.rs`.

## Enabling `rust-analyzer`

Run the command `rustlings lsp` which will generate a `rust-project.json` at the root of the project, this allows [rust-analyzer](https://rust-analyzer.github.io/) to parse each exercise.

## Continuing On

Once you've completed Rustlings, put your new knowledge to good use! Continue practicing your Rust skills by building your own projects, contributing to Rustlings, or finding other open-source projects to contribute to.

## Uninstalling Rustlings

If you want to remove Rustlings from your system, there are two steps. First, you'll need to remove the exercises folder that the install script created
for you:

```bash
rm -rf rustlings # or your custom folder name, if you chose and or renamed it
```

Second, since Rustlings got installed via `cargo install`, it's only reasonable to assume that you can also remove it using Cargo, and
exactly that is the case. Run `cargo uninstall` to remove the `rustlings` binary:

```bash
cargo uninstall rustlings
```

Now you should be done!

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

Development-focused discussion about Rustlings happens in the [**rustlings** stream](https://rust-lang.zulipchat.com/#narrow/stream/334454-rustlings)
on the [Rust Project Zulip](https://rust-lang.zulipchat.com). Feel free to start a new thread there
if you have ideas or suggestions!

## Contributors ✨

Thanks goes to the wonderful people listed in [AUTHORS.md](./AUTHORS.md) 🎉
