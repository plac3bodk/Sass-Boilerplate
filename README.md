# Sass Boilerplate by plac3bodk


## Introduction
A simple boilerplate for Sass projects.

## Architecture

Using the 7-1 pattern from [Sass-guidelin.es ](https://Sass-guidelin.es/#architecture)

    styles/
    |
    |- abstracts/
    |    |- _variables.sass        # Variables
    |    |- _mixins.sass           # Mixins
    |    |- _breakpoints.sass      # Breakpoint manager
    |    |- _placeholders.sass     # Placeholders
    |    |- _extends.sass          # Extends
    |      
    |- base/   
    |    |- _reset.sass            # CSS reset
    |    |- _typography.sass       # Typography rules
    |    |- _globals.sass          # Global classes
    |      
    |- components/
    |    |- _buttons.sass          # Buttons
    |    |-  animations.sass       # Animations
    |    |- _modals.sass           # Modals
    |
    |- layout/
    |    |- _general.sass          # General styles
    |    |- _grid.sass             # Grid layout
    |    |- _header.sass           # Header styles
    |    |- _navigation.sass       # Navigation styles
    |    |- _sidebar.sass          # Sidebar styles
    |    |- _footer.sass           # Footer styles
    |      
    |- pages/
    |    |- _frontpage.sass        # Frontpage styles
    |    |- _textpage.sass         # Textpage styles
    |    |- _contactpage.sass      # Contactpage styles
    |      
    |- themes/
    |    |- _theme.sass            # Main theme
    |      
    |- vendors/
    |    ...                       # Add jQueryUI, Bootstrap etc. here  
    |
    `- main.sass

### Explanations
#### *Coming soon*
