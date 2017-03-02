stage('Build') {
  node('master') {
    git([url: 'https://github.com/SumTotalSystems/RecordRTC.git', branch: 'sumt-master'])
    sh 'npm install'
    sh 'bower install'
    sh 'node_modules/.bin/grunt'
  }
}
