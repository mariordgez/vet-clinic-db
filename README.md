![](https://img.shields.io/badge/Microverse-blueviolet)

# Vet Clinic database

Learn and apply database queries index optimizations

## :hammer: Built With

- PostgreSQL / PgAdmin

To get a local copy up and running follow these simple steps:

1. Go to the [repository page](https://github.com/mariordgez/vet-clinic-db).
2. Press the "Code" button and copy the link.
3. Clone it using git command `git clone git@github.com:mariordgez/vet-clinic-db.git`.
4. In the project folder open the schema.sql with an editor of your preference.
5. Open PG admin and then create a new server with the localhost address, then use the query tool and paste the schema.sql content inside and run it.
6. Run the next queries and verify that the execution time is reduced:

   EXPLAIN ANALYZE SELECT COUNT(_) FROM visits where animal_id = 4;
   EXPLAIN ANALYZE SELECT SELECT _ FROM visits where vet_id = 2;
   EXPLAIN ANALYZE SELECT SELECT \* FROM owners where email = 'owner_18327@mail.com';

## :blue_book: Learning Objectives

- Use EXPLAIN ANALYZE on the previous queries to check what is happening.
- Optimize the queries result time.

## Authors

👨‍💻 **Angel Diaz**

- GitHub: [@ad9311](https://github.com/ad9311)
- Twitter: [@adiaz9311](https://twitter.com/adiaz9311)
- LinkedIn: [ad9311](https://linkedin.com/in/ad9311)

👨‍💻 **Mario Rodriguez**

- GitHub: [@mariordgez](https://github.com/mariordgez)
- Twitter: [@MarioRo75396624](https://twitter.com/MarioRo75396624)
- LinkedIn: [LinkedIn](https://linkedin.com/in/mario-alberto-rodriguez-cota-a2860a205)

## 🤝 :raised_hand: :raised_hand: Contributions

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/mariordgez/vet-clinic-db/issues).

## :grey_exclamation: Acknowledgments

- [Microverse](https://www.microverse.org/)
