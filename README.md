1. Within a Github action that runs whenever code is published, since running automated test in Github action means whenever code is pushed, tests are automatically verified with changes and checks if something breaks.
2. No, E2E tests are for the testing of the whole application from the user POV.
3. Navigation mode analyzes websites as they load from scratch, such as how fast an efficiently the whole page can load to get a full E2E performance review. Snapshot mode instead captures the current DOM and helps evaluating the page as is without interaction.
4. 1. Optimizing images since they're extremely large and slow
2. Removing unused JS since lighthouse may show unused loaded and unused scripts.
3. Greater accessibility as images and buttons might lack their altenrative labels.