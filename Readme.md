com.github.pre
==============

A simple plugin for the DITA open toolkit which provides to ant the information of your git repository.
The information could be passed to the xslt code. The parameters are already defined in this plugin
for the XHTML and PDF transtype.

```bash
  [echo] #Ant properties
  [echo] #Thu Sep 25 13:33:03 EDT 2014
  [echo] git.info.commit.branch=your-feature-branch
  [echo] git.info.commit.count=1211
  [echo] git.info.commit.hash=06b9c63099b3071b077fc80eb45dd52214b8fde9
  [echo] git.info.repo.name=your-repo
  [echo] git.info.repo.path=/absolute/path/to/your-repo
  [echo] git.info.repo.url=git@github.com\:your-account/your-repo.git
```

If the DITA file is not part of a git repository, the ant property will be emptyé

You must have git availaible by command line in order to use this module.

