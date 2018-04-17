# Enhancv style JSX for Prettier

This is a small tweek of [prettier](https://github.com/prttier/prettier). Multiline attributes are indented with only one space, and `jsxBracketSameLine` defaults to true. This produces better output for large nested JSX files. The pros/cons of this have been discussed in this [prettier PR](https://github.com/prettier/prettier/pull/2082)

Also if there are more than 1 attribute in a JSX tag, we expand them to be multiline.


## Usage

Install:

```
yarn add prettier-ecv --dev
```

You can install it globally if you like:

```
yarn global add prettier-ecv
```



## Full documentation at https://github.com/prettier/prettier
