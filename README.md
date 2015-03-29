# Serverkit
Configuration management toolkit.

## Usage
```sh
# Create Gemfile
bundle init

# Install serverkit and its dependencies
echo 'gem "serverkit"' >> Gemfile
bundle install

# Write your recipe
vi recipe.yml

# Check
bundle exec serverkit check --recipe=recipe.yml

# Apply
bundle exec serverkit apply --recipe=recipe.yml
```
