## Installation

```
curl -sL https://github.com/emacsfodder/es6-mocha-yasnippets/archive/master.tar.gz | tar xz
```

Assuming you downloaded to `~` install via `M-x package-install-file`
`~/master.tar.gz`

## Emacs yasnippets for mocha / es6

Just a few useful snippets for Mocha using ES6 style.

#### Main BDD constructs

- `desc` <kbd>TAB</kbd>

    describe block

- `befr` <kbd>TAB</kbd>

    before / beforeEach block

- `aftr` <kbd>TAB</kbd>

    after / afterEach block

- `it` <kbd>TAB</kbd>

    it block

#### xUnit constructs

- `test` <kbd>TAB</kbd>

    xUnit style flat test

- `suite` <kbd>TAB</kbd>

    xUnit style test suite

#### Expect & Chai Matchers/Chains

- `ex` <kbd>TAB</kbd>

    expect

- `m` <kbd>TAB</kbd>

    all chai matchers/chains (select from the list, **ido/flx** is highly
    recommended as your yas dropdown style)

    - `.to`
    - `.be`
    - `.been`
    - `.is`
    - `.that`
    - `.which`
    - `.and`
    - `.has`
    - `.have`
    - `.with`
    - `.at`
    - `.of`
    - `.same`
    - `.not`
    - `.deep`
    - `.any`
    - `.all`
    - `.a(type)`
    - `.include(value)`
    - `.ok`
    - `.true`
    - `.false`
    - `.null`
    - `.undefined`
    - `.NaN`
    - `.exist`
    - `.empty`
    - `.arguments`
    - `.equal(value)`
    - `.eql(value)`
    - `.above(value)`
    - `.least(value)`
    - `.below(value)`
    - `.most(value)`
    - `.within(start, finish)`
    - `.instanceof(constructor)`
    - `.property(name, [value])`
    - `.ownProperty(name)`
    - `.ownPropertyDescriptor(name[, descriptor[, message]])`
    - `.length`
    - `.lengthOf(value[, message])`
    - `.match(regexp)`
    - `.string(string)`
    - `.keys(key1, [key2], […])`
    - `.throw(constructor)`
    - `.respondTo(method)`
    - `.itself`
    - `.satisfy(method)`
    - `.closeTo(expected, delta)`
    - `.members(set)`
    - `.oneOf(list)`
    - `.change(function)`
    - `.increase(function)`
    - `.decrease(function)`
    - `.extensible`
    - `.sealed`
    - `.frozen`

## Contributing

Your contributions are welcome, please submit a pull request to add
new snippets, or raise issues / corrections.
