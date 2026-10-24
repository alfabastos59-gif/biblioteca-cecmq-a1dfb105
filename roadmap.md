# Original archive publication
- [x] Confirm combined name search and nationality filtering in the authors directory; verified matching results, empty state, and reset.
- [x] Create the public authors page from banco_autores_pensador-2.json with mapped photos, biographies, and quotations; verified search, nationality filter, profile dialog, and mobile layout.
- [ ] Restore the uploaded application's original screens and behavior.
- [ ] Verify public screens, assets, and publication security checks.
- [ ] Request publication of the restored version.
- [ ] Verify authenticated data flows (requires an available account and data access).

# Standalone authors page package
- [x] Move the authors theme out of src/styles.css into src/features/authors/authors.css so the page module is self-contained.
- [ ] Build the ZIP with the authors page source, data, portraits, README (file structure + integration steps), and dependency list; verify entries and copy to Files.
- [ ] Verify the /autores page still renders correctly after the theme move (search, nationality filter, detail dialog).
