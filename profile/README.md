## Welcome to the Autoware Foundation! 👋
![Autoware stack](https://static.wixstatic.com/media/984e93_552e338be28543c7949717053cc3f11f~mv2.png/v1/crop/x_0,y_1,w_1500,h_879/fill/w_1079,h_633,al_c,usm_0.66_1.00_0.01,enc_auto/Autoware-GFX_edited.png)

The Autoware Foundation manages the development of Autoware, the world's leading open-source software project for autonomous driving, and sponsors Autoware-based projects all over the world. Autoware was started in 2015 and is being used by over 100 companies on more than 30 vehicles in over 20 different countries worldwide. 

### Repository overview
- [autowarefoundation/autoware](https://github.com/autowarefoundation/autoware)
  - Meta-repository containing `.repos` files to construct an Autoware workspace.
  - It is anticipated that this repository will be frequently forked by users, and so it contains minimal information to avoid unnecessary differences.
- [autowarefoundation/autoware_common](https://github.com/autowarefoundation/autoware_common)
  - Library/utility type repository containing commonly referenced ROS packages. 
  - These packages were moved to a separate repository in order to reduce CI execution time
- [autowarefoundation/autoware.core](https://github.com/autowarefoundation/autoware.core)
  - Main repository for high-quality, stable ROS packages for Autonomous Driving.
  - Based on [Autoware.Auto](https://gitlab.com/autowarefoundation/autoware.auto/AutowareAuto) and [Autoware.Universe](https://github.com/autowarefoundation/autoware.universe).
- [autowarefoundation/autoware.universe](https://github.com/autowarefoundation/autoware.universe)
  - Repository for experimental, cutting-edge ROS packages for Autonomous Driving.
  - Autoware Universe was created to make it easier for researchers and developers to extend the functionality of Autoware Core
- [autowarefoundation/autoware_launch](https://github.com/autowarefoundation/autoware_launch)
  - Launch configuration repository containing node configurations and their parameters.
- [autowarefoundation/autoware-github-actions](https://github.com/autowarefoundation/autoware-github-actions)
  - Contains [reusable GitHub Actions workflows](https://docs.github.com/ja/actions/learn-github-actions/reusing-workflows).
  - Since Autoware has many repositories, making CI scripts DRY is efficient.
- [autowarefoundation/autoware-documentation](https://github.com/autowarefoundation/autoware-documentation)
  - Documentation repository for Autoware users and developers.
  - Since Autoware Core/Universe has multiple repositories, a central documentation repository is more user-friendly than writing distributed documentation in each repository.

### Contribution guidelines
[There is no formal process to becoming a contributor!](https://github.com/autowarefoundation/autoware-projects/wiki#contributors). If you want to become a contributor then you can comment on any [existing issues](https://github.com/autowarefoundation/autoware.universe/issues) or make a pull request on any Autoware repository. 

Before jumping in, we do recommend taking a look at Autoware's [working groups](https://github.com/autowarefoundation/autoware-projects/wiki#working-group-list) to see how Autoware projects are managed and to gain an understanding of any work in progress.

If you have any questions or ideas, feel free to start a discussion on [GitHub Discussions in autowarefoundation/autoware](https://github.com/autowarefoundation/autoware/discussions).

### Useful resources
- [Autoware documentation](https://autowarefoundation.github.io/autoware-documentation/main/) (also [open source](https://github.com/autowarefoundation/autoware-documentation)!)
- 

### Appendix
For more information about the Autoware Foundation and Autoware itself, check out our [homepage](https://www.autoware.org/). 
