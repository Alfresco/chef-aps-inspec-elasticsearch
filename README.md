# chef-aps-inspec-elasticsearch Inspec Profile

Inspec profile for [chef-aps-elasticsearch](https://github.com/Alfresco/chef-aps-elasticsearch) and [chalf-img-aws-elasticsearch](https://github.com/Alfresco/chalf-img-aws-elasticsearch/) cookbook

To use it in your Kitchen suite add:

```
verifier:
  inspec_tests:
    - name: chef-aps-inspec-elasticsearch
      git: https://github.com/Alfresco/chef-aps-inspec-elasticsearch
```

This Profile depends on [chef-alfresco-inspec-utils](https://github.com/Alfresco/chef-alfresco-inspec-utils) to import libraries and matchers
