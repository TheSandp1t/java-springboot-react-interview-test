# java-springboot-react-interview-test
Java springboot and React project meant for interviews

---

## Instructions

### 1. Fork this repo with your own Github account.

### 2. Implement the following:

#### a. In the Spring Boot source code <b>ClientsController.java</b>, implement the following:

i. Implement a <u>get</u> method that sorts a given array in alphabetical order.

ii. Implement a <u>get</u> method that integrates with https://dictionaryapi.dev/ and get the definition(s) of <i>durian</i>.

iii. Implement a <u>get</u> method that use the word <i>rainbow</i>, and returns an array of objects, where each character is the label and is assigned to a random colour. Each object should have the format of { label: "a", colour: "#000000" }.

#### b. In the ReactJS source code <b>Home.js</b>, implement the link to a new page. Implement this new page which shows the response from the calls in 2.a.

You are recommended to clone the <u>ClientList.js</u> page to help you implement the new page.

### 3. Create a pull request (PR) from your forked repo to our repo (https://github.com/EMQ2/javascript-interview-projec)

### 4. Send the PR link back to us for our assessment of your implementation

### 5. Wait for the results!

---

## Setup
This will provide a high-level overview on how you can setup the project to begin your development. You are expected to resolve issues as needed to meet the objectives requested of you.

1. Install Maven and its pre-requisites.

2. Using the terminal, run the following command at the root working directory

```bash
mvn spring-boot:run
```

### Relevant Articles:

This interview project was created using the following tutorial as base:

- [CRUD Application With React and Spring Boot](https://www.baeldung.com/spring-boot-react-crud)

IDE and extensions used (you can use others):

- [Visual Studio Code](https://code.visualstudio.com/Download)
- [Java build tools in VS Code](https://code.visualstudio.com/docs/java/java-build)
- [Spring boot extension pack](https://marketplace.visualstudio.com/items?itemName=vmware.vscode-boot-dev-pack&ssr=false)

### Others

For MacOS, I installed Maven using Homebrew:

```bash
brew install maven
```
