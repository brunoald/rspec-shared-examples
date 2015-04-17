# Shared examples

Create a ````support```` folder inside spec folder.

Add the following snippet to ````spec_helper.rb```` file:

````Dir["./spec/support/**/*.rb"].sort.each { |f| require f}````

More examples below:

https://www.relishapp.com/rspec/rspec-core/docs/example-groups/shared-examples