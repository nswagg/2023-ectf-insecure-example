[Ceedling](https://github.com/ThrowTheSwitch/Ceedling) Testing Module with Mitre eCTF [insecure example](https://github.com/mitre-cyber-academy/2023-ectf-insecure-example) as a subtree for testing. 

Additional tools and tips: 
- [Add Unit Testing to Embedded Systems](https://www.electronvector.com/blog/add-unit-tests-to-your-current-project-with-ceedling)
- [Using Ceedling and CMock](https://blog.zaleos.net/unit-testing-c-code-with-ceedling-and-cmock/)
- [Replace CMock with Fake function framework (FFF)](https://github.com/ElectronVector/fake_function_framework/tree/f89ae3f0945a76333f48db6e6f654a76acd12e3a)
- [Working with Git Subtrees (and subtree merging)](https://www.atlassian.com/git/tutorials/git-subtree)

`ceedling`  commands can be run within the `test_eCTF` directory. Common commands: 
>   ceedling files:source # shows available source files
>   ceedling test:all # Runs all available tests from /test directory
>   ceedling module:create[<nameOfFile>] # Creates a new test file from source file <nameOfFile>