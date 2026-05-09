Prepared split files

- train_split.csv: stratified 80% split from labeled rows in train.csv (2,188 rows)
- valid_split.csv: stratified 20% split from labeled rows in train.csv (548 rows)
- unlabeled_rows.csv: rows from train.csv where sii is blank (1,224 rows)

Notes:
- test.csv was not mixed into the supervised split.
- sii is kept only in the labeled split files and is blank only in the unlabeled export.
