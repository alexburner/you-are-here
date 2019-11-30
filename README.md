# you-are-here

Great chain of being, our place in an emergent complex universe

## Scripts

```sh
# Installation
npm install  #  download all dependencies

# Development
npm run dev   # rm -rf ./dev && parcel --out-dir dev ./src/index.html
npm run tsc   # tsc --watch --noEmit

# Production (outputs to docs/)
npm run build  # rm -rf ./docs && parcel build --out-dir ./docs --public-url ./ ./src/index.html

# Code formatting (optional: most editors can handle these themselves)
npm run format    # npm run tslint && npm run prettier
npm run prettier  # prettier --write 'src/**/*.+(ts|tsx|json|html|scss)'
npm run tslint    # tslint --fix --project tsconfig.json 'src/**/*.+(ts|tsx)'
```
