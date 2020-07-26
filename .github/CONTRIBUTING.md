# How to Contribute

We welcome contributions from the community. Here are a few ways you can help us improve.

## Open an Issue

If you see something you'd like changed, but aren't sure how to change it, submit an issue describing what you'd like to see.

## Submit a Pull Request

If you feel like getting your hands dirty, feel free to make the change yourself. Here's how:

1. Fork the repo on Github, and then clone it locally.
2. Create a branch named appropriately for the change you are going to make.
3. Make your code change.
4. If you are creating a new role, please add a test for it in our [testing playbook.](https://github.com/redhat-cop/tower_configuration/blob/devel/playbooks/example_with_yaml/configure_tower.yml) by adding a new role entry and adding the appropriate yaml file with test data in the tower_configs directory.
5. Push your code change up to your forked repo.
6. Open a Pull Request to merge your changes to this repo. The comment box will be filled in automatically via a template.
7. All Pull Requests will be subject to Ansible and Yaml Linting checks. Please make sure that your code complies and fix any warnings that arise. These are Checks that apear at the bottom of your Pull Request.
8. All Pull requests are subject to Testing against being used in tower. As above there is a check at the bottom of your pull request for this named integration.

See [Using Pull Requests](https://help.github.com/articles/using-pull-requests/) got more information on how to use GitHub PRs.

For an in depth guide on how to contribute see [this article](https://opensource.com/article/19/7/create-pull-request-github)
