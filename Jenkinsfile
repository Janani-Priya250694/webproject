node {
def applicationTitle = 'Learning application';

stage('chekout code')
{
git branch: 'master', url: 'https://github.com/Janani-Priya250694/webproject.git'
}
stage('copy HTML')
{
sh cp index.html /var/www/html/'
}
}
