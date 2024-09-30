name: prepare quizapp

on: [push]

jobs:
  build:
    runs-on: [self-hosted]
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with: 
          node-version: 18
      - run: npm ci
      - run: npm start
