# Gemfile
source "https://rubygems.org"

# Utiliser la gem 'github-pages' car vous déployez sur GitHub Pages
# Elle inclut Jekyll et de nombreux plugins compatibles.
# gem "github-pages", "~> 232" # <--- Utilisez cette version pour github-pages

# Vous n'avez PAS besoin de spécifier la gem "jekyll" séparément si vous utilisez "github-pages"
# gem "jekyll", "~> 4.3.2" # Commenter ou supprimer cette ligne si présente

group :jekyll_plugins do
  # jekyll-feed est déjà inclus par github-pages, mais le lister ne fait pas de mal
  # et peut clarifier l'intention si vous l'utilisez explicitement.
  gem "jekyll-feed" # Pas besoin de spécifier la version ici si elle est gérée par github-pages

  # jekyll-toc est un plugin que vous avez ajouté et qui est compatible avec GitHub Pages.
  # Il est bon de le lister explicitement ici.
  gem "jekyll-toc", "~> 0.16" # Vous pouvez le laisser comme ça ou vérifier la dernière version stable
  gem "tzinfo-data", "~> 1.2" # <--- MODIFIEZ OU AJOUTEZ CETTE LIGNE
  # gem 'wdm', '>= 0.1.0' if Gem.win_platform? # Optionnel: pour une meilleure auto-régénération sur Windows
end

# Optionnel: Pour faire disparaître l'avertissement 'bigdecimal' si vous êtes sur Ruby 3.4.0 ou supérieur
# gem 'bigdecimal'
