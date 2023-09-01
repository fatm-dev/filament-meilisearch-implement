
# Filament meilisearch global 

Just one file to change Filament global search driver to meilisearch.

## Installation

Place file `MeilisearchGlobalSearchProvider.php` where you want to store it. Then in your `panelProvider`

```
use App\Filament\Plugins\MeilisearchGlobalSearchProvider;

    return $panel
        ...
        ->globalSearch(MeilisearchGlobalSearchProvider::class)

```
## Contributing

Contributions are always welcome! Especially since I didn't implement `caseSensitive` and `searchableAttributes` )
    
