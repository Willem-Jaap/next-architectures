<h1 align="center"><b>Next.js Architectures</b></h1>

<h3>
  <b>⚠️ Warning: This repo is a work in progress ⚠️</b><br>
  <sub>Not all examples are working yet.</sub>
  <br>
  <sub>These subrepos are a demonstration of how to split files, not an implementation which is tested through and trough.</sub>
</h3>
<br>
<hr>
A collection with different types of Next.js architectures. Different applications require different architectures. in this monorepo different ideas to structure Next projects are explored.
<br>
<hr>

## Architectures

### [Feature based](./next-feature-based)

A feature based architecture is a good starting point for most projects. It is easy to understand and easy to scale. It is also easy to add new features.

Every feature is a folder in the `features` folder.

Feature examples

-   `auth`
-   `blog`
-   `dashboard`
-   `profile`

### [Type based](./next-type-based)

The type based architecture is a way of seperating files into a folder with files of the same type.

For example all pages are in the `pages` folder, all components are in the `components` folder.

Other types:

-   `hooks`
-   `lib`
-   `styles`
-   `utils`
-   `types`
