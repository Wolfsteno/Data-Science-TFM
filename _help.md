Comando de CMD para listar todos los directorios y archivos en el directorio actual
dir /s

Este comando se utiliza para limpiar ficheros pesados y asi no se subiran a GitHub
git filter-branch --force --index-filter "git rm --cached --ignore-unmatch data-sets/WIN/item_prices.csv data-sets/WIN/item_sales.csv" --prune-empty --tag-name-filter cat -- --all

Esto es un test para ver como se hace un commit