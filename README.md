# Development

This repository is for the discussion of development ideas for the [spiketools](https://github.com/spiketools/spiketools) module for analyzing single-unit neural activity.

The goal of this repository is to separate out code and maintenance questions for the `spiketools` package from discussion of ideas and a place to organize on topics about additions or substantial changes to the module.

As a rule of thumb, if an idea or question is about the code in the project, it's likely a code or maintenance problem, whereas if an idea is about the concepts and approach, it's likely a development idea.

### Code or Maintenance Questions

Anything that relates to a bug report, an implementation question, requesting help for using the module, or a feature request that doesn't required a major update (for example, a new function in an existing module, or an extension of an existing functionality) is considered a code or maintenance issue.

Code or maintenance questions should be directed to [issues page](https://github.com/spiketools/spiketools/issues) of the [main repository](https://github.com/spiketools/spiketools).

### Development Ideas

By development ideas, we mean ideas for a new tool or conceptual approach to be added or drastically changed in `spiketools`. This can also include discussion of best practices and tutorial materials for how we want to recommend usage of the tool, and of spike analyses more generally. Anything that would require a new major release to the codebase is a development idea. 

For example, the following would all be considered development ideas:
- significant changes to an underlying algorithm in the module, and how it works
- additions of new algorithms, functions or sub-modules to the package
- a suggestion to operate on a different kind of data or different inputs

For any ideas that fall into this category, please open an [issue](https://github.com/spiketools/development/issues) in this repository. 

Once an issue is opened, this repository can then be used by `spiketools` developers to discuss and explore these ideas. If an idea is decided upon, a plan will be made for implementation, which can move to a fork or branch of the core repository, once the idea is translated into code tasks. 
