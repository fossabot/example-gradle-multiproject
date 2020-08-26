# [Codecov][1] Gradle Example
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fcodecov%2Fexample-gradle-multiproject.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fcodecov%2Fexample-gradle-multiproject?ref=badge_shield)


1. Set-up your `build.gradle` for collecting coverage in multiproject gradle projects and compiling their coverage with jacoco. [See here](https://github.com/codecov/example-gradle-multiproject/blob/master/build.gradle#L57)
2. Execute your tests as normal
3. Call `gradle codeCoverageReport` to generate report. [See here](https://github.com/codecov/example-gradle-multiproject/blob/master/.travis.yml#L13)
4. Call `bash <(curl -s https://codecov.io/bash)` to upload reports to Codecov. [See here](https://github.com/codecov/example-gradle-multiproject/blob/master/.travis.yml#L16)
  - Public project? Using TravisCI, CircleCI or AppVeyor? You're all set! No upload token required.
  - Otherwise please include your repository upload token. [See here](http://docs.codecov.io/v4.3.0/docs/about-the-codecov-bash-uploader#section-upload-token)

[1]: https://codecov.io/


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fcodecov%2Fexample-gradle-multiproject.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fcodecov%2Fexample-gradle-multiproject?ref=badge_large)