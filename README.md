# Install

Copy the script in the home folder,
Just modify your .bashrc to alias a command for execution

```bash
  alias f='ruby ~/.rails-shortcuts.rb'
```

Just insert your base project directory in which you wish the searching to stop at,
For myself all my work is in a Projects folder in my home folder, so my base project directory is '/Users/idle/Projects'.

```ruby
  base = '/Users/idle/Projects'
```

# Usage

Just type f routes anywhere in a project to pull up the routes.rb file and f gemfile to pull up the Gemfile in vim.

# Non vim user?

Replace the exec commands with your own text editor

```ruby
  exec "emacs #{routes_path}"
```
