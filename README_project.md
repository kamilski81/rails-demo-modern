# rails-modern-demo
Modern Day Rails in Action

# Commands used to create this demo app
```bash
brew install mise
echo 'eval "$(mise activate zsh)"' >> ~/.zshrc
mise activate zsh
mise use ruby@3.4.4 # Use the latest stable Ruby version
mise install # Install the Ruby version
gem install rails
```

# Create the Rails app
```bash
rails new rails-modern-demo --css=tailwind --database=postgresql --skip-kamal
```