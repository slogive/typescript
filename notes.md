Watch with the compilator

tsc -W \*.ts

Init config file for TS
tsc --init

compile on save
"compileOnSave": true

Include custom config and exclude
"include": [
"src/**/*.ts
]

"exclude": [
"node_modules",
"**/*.test.ts"
]
