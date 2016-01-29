# What it is
 * Haml (HTML abstraction markup language) is based on one primary principle: markup should be beautiful. It’s not just beauty for beauty’s sake either; Haml accelerates and simplifies template creation down to veritable haiku.
 * Why I like HAML:
    - Much easier to write and read then erb
    - Faster to work with
    - Looks clean and crisp

# Getting Set Up With HAML
 * In your rails Gemfile add the HAML gem
     - gem 'haml'
 * Next Bundle install your Gem
     - In your terminal, run bundle install

# Convert your .html.erb files to .html.haml
     - Any files in your views that you plan to use haml in you must change your extension
     
# Quick tips to get you started
 * ERB
   - `<strong><%= item.title %></strong>`
 * HAML
   - `%strong= item.title`

 * Adding Attributes
   - HTML
     * `<strong class="code" id="message">Hello, World!</strong>`
   - HAML
     * `%strong{:class => "code", :id => "message"} Hello, World!`
 * `%p`
 * `%img(src="#")`
 * `.nav`
	 - `%ul.nav_items`
		  - `%li= link_to "Home", :title => 'Home'`
		  - `%li= link_to "About Us", :title => 'About Us'`
	    -	`%li= link_to "Contact", :title => 'Contact'`


For more info, head to [haml.info](http://haml.info/tutorial.html).

Source: haml.info
