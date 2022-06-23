node {
// Checkout
git branch: ‘master’,url: ‘https://github.com/Jaykgehlot/Testhtml-.git';

// install required bundles
sh ‘bundle install’

// build and run tests with coverage
sh ‘bundle exec rake build spec’

// Archive the built artifacts
archive (includes: ‘pkg/*.gem’)

git 'https://github.com/Jaykgehlot/Testhtml-.git'

}
