# A file for undesided things that need a discussion

## Importing of files based on routes

### Description

The importing of files is normaly done though a import property e.g. `import: component`.
But how should this be done with route based files should they be imported the same way or get automaticly imported.

### Examples

```nml
{
    import: component;
    // ^ normal import

    import: base.dynamic(this, page);
    // import dynamic subpages based on this page position e.g. import only subpages and not the page itself
}
```
