# Hugo Starter Site

This project is meant to be cloned for future websites. The idea is to have a centralized code-base for the content to sit on top of, with changes being able to be applied to multiple sites without affecting content.

Each subsequent clone is meant to have individual design assets associated with its respective project, all relying on a shared set of pre-built functionality and reference names. As such, the default Hugo-

Additionally, a shared set of NPM packages will be baked into each project, with configuration for each module

More documentation to come.

## Theme: Tailwind Starter

The framework used for creating each site will be Tailwind-CSS. This is loaded as a submodule in the 'themes/' folder, and is merely a way to pipeline Tailwind and additional NPM components into the framework. Each sites respective design will be handled in the root Hugo layout folder, rather than the theme folder.