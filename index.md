## Benefits of Sourcegraph and OSS


### Easier Workflow For Maintainers

- **To sunset or not to sunset?** 
  - When making decisions around sunsetting features, Sourcegraph’s cross-repo search allows visibility on the usage of the feature. OSS maintainers can then make an informed decision on the impact of the deprecation.
- **Code Intelligence on pull requests** 
  - Common scenario: You get a pull request from an unknown person. With Sourcegraph, you don’t need to check out their code, can give high quality reviews faster and respond quicker, which in turn helps attract more contributors.
- **Extra code care**
  - Use [Saved Searches & Code Monitoring](https://docs.sourcegraph.com/code_search/how-to/saved_searches) to get notified about specific code changes that might need extra care and attention.
- **Who uses it?**
  - Find out who uses your project with Sourcegraph’s universal code search.

### Contribute Faster

- **Speedy Understanding** 
  - Use Sourcegraph to get up to speed with unknown code as you can read and understand code much faster with go to definition/find all references, get a better overview of the interdependence of code (find all references) and find whatever you need independently.
- **Informed decisions** 
  - Use Sourcegraph to justify propositions on feature requests or changes. Here is an [example](https://github.com/golang/go/issues/45494) of a Go lang contributor opting to add an experimental value on an interface vs refactoring. He shares a Sourcegraph search revealing that there is a significant number of repositories depending on the current layout.
- **Quality contributions**
  - Sourcegraph’s extensions like CodeCov visualize the test coverage of code contributions.


### Safer OSS Adaptations

- **Urgent changes made easy** 
  - OSS libraries can have security vulnerabilities and need to be replaced ASAP. Sourcegraph makes it easier to find vulnerable code cross-repository and across all code hosts. You can then easily replace the affected library with [batch changes](https://about.sourcegraph.com/batch-changes/).
- **Dependency changed? No problem.** 
  - When a dependency has experienced a breaking change you can use diff search to find when they made the change to try and gather more context and you can adjust to the changes accordingly.
- **Learn by example**
  - When wanting to use a new library or component, find other projects that use it and learn from their example.
  
 
### What's coming up next?

- [API Docs](https://about.sourcegraph.com/blog/api-documentation-for-all-your-code/) - Understand and see use cases of APIs. 
- [Notebooks](https://sourcegraph.com/github.com/novoselrok/sourcegraph-notebooks/-/blob/test-notebook.snb.md) - Search docs/markdown easier, onboard quicker and enhance documenting (interactive and dynamic).
