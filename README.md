# uru-databases-1-rush-cargo

Source code and documentation for Rush Cargo, a university database project by students of Universidad Rafael Urdaneta in Maracaibo, Venezuela. Rush Cargo is a fictional company that handles national and international shipping, including ocean and air freight.

**Note:** This repository is archived and read-only. Rush Cargo is not a registered trademark and was built for learning purposes only, not for profit.

The name reflects the aim of a fast approach to moving packages across cities, regions and countries. "Rush" also hints at Rust, the main language of the application, and "Cargo" at the Rust package manager.

---

## Project structure

- **`rushcargo-app/`** — Rust application (`Cargo.toml`, `migrations/`, `src/`).
- **`rushcargo-insiders/`** — Python app (`main.py`, `app.py`, `lib/`, `requirements.txt`, `example.env`).
- **`setup/`** — SQL scripts: `constraints.sql`, `views.sql`, `final.sql`.
- **`model/`** — entity-relationship (MER) and relational (MR) model diagrams.
- **`AllCars/`** — additional `model` and `setup` files.

## Documents

- Roadmap ([Spanish version](https://docs.google.com/document/d/1MupYuTTxXraIwLAzVZR1WUXree8AxoY6v4uSUJRZCWk/edit?usp=sharing)).

## Development team

- Ramón Álvarez ([ralvarezdev](https://github.com/ralvarezdev)) — Database Modeler and Programmer.
- Rebecca Bracho ([Beckarby](https://github.com/Beckarby)) — Database Modeler.
- Jesús Meléndez ([JeJaMel](https://github.com/JeJaMel)) — Database Administrator.
- Javier Pérez ([Kaucrow](https://github.com/Kaucrow)) — Programmer. Forever remembered by the team. Rest in peace, dear friend.

## Requirements

### Week 1

- Create, delete and modify shipments that have not yet left their initial location.
- Display information about packages that have already left their initial location.
- Display shipping statistics for truck drivers.
- Register the locations packages have traversed.
- Display the packages a vehicle will carry on a given day.

### Week 2

- Package administrators can create their own routes and select which drivers carry which packages at specific locations.
- Display the contents of packages shipped by a provider to a retail store, with statistics.
- Clients can have one locker in each country, holding at most 5 packages at a time.
- The total weight of the packages in a locker must be 200 kg or less.

---

## License

GNU General Public License v3.0. See [`LICENSE`](LICENSE).
