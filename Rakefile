require 'rake/testtask'

task :default => [:test]

task :clean do
  sh 'rm -rf _site .sass-cache'
end

task :build do
  sh 'bundle exec jekyll build'
end

task :test do
  ruby "tests/test_helper.rb"
end