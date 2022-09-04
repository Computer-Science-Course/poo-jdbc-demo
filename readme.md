### Observação:
Modificar o arquivo `db.example.properties` para `db.properties` e preencher com os dados sensíveis locais.

### Output:

```bash
=== TEST 1: seller findById =====
Seller [id=3, name=Alex Grey, email=alex@gmail.com, birthDate=1988-01-15, baseSalary=2200.0, department=Department [id=1, name=Computers]]

=== TEST 2: seller findByDepartment =====
Seller [id=6, name=Alex Pink, email=bob@gmail.com, birthDate=1997-03-04, baseSalary=3000.0, department=Department [id=2, name=Electronics]]
Seller [id=2, name=Maria Green, email=maria@gmail.com, birthDate=1979-12-31, baseSalary=3500.0, department=Department [id=2, name=Electronics]]

=== TEST 3: seller findAll =====
Seller [id=3, name=Alex Grey, email=alex@gmail.com, birthDate=1988-01-15, baseSalary=2200.0, department=Department [id=1, name=Computers]]
Seller [id=6, name=Alex Pink, email=bob@gmail.com, birthDate=1997-03-04, baseSalary=3000.0, department=Department [id=2, name=Electronics]]
Seller [id=1, name=Bob Brown, email=bob@gmail.com, birthDate=1998-04-21, baseSalary=1000.0, department=Department [id=1, name=Computers]]
Seller [id=5, name=Donald Blue, email=donald@gmail.com, birthDate=2000-01-09, baseSalary=4000.0, department=Department [id=3, name=Fashion]]
Seller [id=2, name=Maria Green, email=maria@gmail.com, birthDate=1979-12-31, baseSalary=3500.0, department=Department [id=2, name=Electronics]]
Seller [id=4, name=Martha Red, email=martha@gmail.com, birthDate=1993-11-30, baseSalary=3000.0, department=Department [id=4, name=Books]]

=== TEST 4: seller insert =====
Inserted! New id = 7

=== TEST 5: seller update =====
Update completed

=== TEST 6: seller delete =====
Enter id for delete test: 
```