
pipeline {
agent any
stages {
stage('Checkout') {
steps {
git branch: 'main', url: 'https://github.com/your-repo.githttps://github.com/bmadhav349-tech/LabExternal1.git'
}
}
stage('Build') {
steps {
echo 'Compiling code...'
}
}
stage('Commit Info') {
steps {
powershell 'git log -1 --pretty=%B' // use 'sh' on Linux
}
}
}
}
