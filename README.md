# dba120-exam1

## Ex. 1
[ch5_ex1.sql](ch5_ex1.sql)

```
INSERT INTO
  terms (terms_id, terms_description, terms_due_days)
VALUES
  ('6', 'Net due 120 days', '120');
```

The SQL query added a record to the terms table.

![images](ch5_ex1_results.jpg)

## Ex. 2
[ch5_ex2.sql](ch5_ex2.sql)

```
UPDATE
  terms
SET
  terms_description = 'Net due 125 days',
  terms_due_days = '125'
WHERE
  terms_id = 6;
```

The SQL query updated a record in the terms table.

![images](ch5_ex2_results.jpg)

## Ex. 3
[ch5_ex3.sql](ch5_ex3.sql)

```
DELETE FROM
  terms
WHERE
  terms_id = 6;
```

The SQL query deleted a record from the terms table.

![images](ch5_ex3_results.jpg)


## Ex. 4
[ch5_ex4.sql](ch5_ex4.sql)

```
INSERT INTO
  invoices
VALUES
  (default, 32, 'AX-014-027', '2018-08-01', 434.58, 0.00, 0.00,2, '2018-08-31', null);
```

The SQL query created a record in the invoices table.

![images](ch5_ex4_results.jpg)



