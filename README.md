stage ('Git Checkout') {
  steps {
      git branch: 'main', URL: 'https://<token>@github.com/username/repoName.git'
     }
  }
