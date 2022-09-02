# xtadeushx-JSFEPRESCHOOL2022Q2

Private repository for @xtadeushx

# run code below to instal eslint with all dependencies

npm i --save-dev eslint-config-airbnb eslint-config-prettier eslint-plugin-html eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier prettier

# ru code bellow to install lint-staged and Husky

npx mrm lint-staged

# ad script to your JSON fie

"scripts": {
"lint": "eslint ./src",
"lint:fix": "eslint ./src --fix"
},

# and

"lint-staged": {
"_": "prettier --write",
"_.js": [
"npm run lint:fix",
"git add"
]
}
