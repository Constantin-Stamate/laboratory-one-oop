# Movie Store – OOP Lab 1

This Java console application simulates a basic **Movie Store**, allowing users to manage a collection of movies by genre, release year, and rating. It demonstrates fundamental principles of **Object-Oriented Programming (OOP)** such as encapsulation, composition, and method-based filtering.

## Laboratory Context

This project was developed as part of **Laboratory 1** for the course **Object-Oriented Programming (OOP)** at the **Technical University of Moldova (UTM)**.

## Structure

The project contains 3 main Java classes:

### 1. `Movie.java`

Represents a single movie object with the following attributes:
- `title` – the name of the movie
- `director` – director's name
- `genre` – movie genre (e.g., Action, Sci-Fi)
- `releaseYear` – year of release
- `rating` – rating score (e.g., IMDb)

### 2. `MovieStore.java`

Handles a list of movies and provides filtering and sorting operations.

**Key methods:**

- `addMovie(Movie movie)` – adds a movie to the store  
- `filterByGenre(String genre)` – returns a list of movies by genre  
- `sortByReleaseYear()` – returns movies sorted by release year  
- `getRatedMovies(int n)` – returns top n rated movies

### 3. `Main.java`

Entry point of the application that:

- Creates a MovieStore  
- Adds several movies  
- Demonstrates filtering, sorting, and rating-based selection

## Useful Links

- [Official Java Documentation](https://docs.oracle.com/en/java/javase/)
- [Java Tutorials - Oracle](https://docs.oracle.com/javase/tutorial/)
- [Stream API Guide](https://docs.oracle.com/javase/8/docs/api/java/util/stream/package-summary.html)

## How to Run the Project

1. **Install Java (JDK 8 or later)**  
   Download and install from the official source: [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)


2. **Clone or download the project files**

```bash
  git clone https://github.com/Constantin-Stamate/Laborator_1_OOP.git
```

3. **Navigate to the project directory**
```bash
  cd Laborator_1_OOP
```

4. **Compile the Java files**
```bash
  javac Main.java Movie.java MovieStore.java
```

5. **Run the application**
```bash
  java Main
```

## Author

This project was developed as part of the **Object-Oriented Programming** course at **Technical University of Moldova (UTM)**.

- GitHub: [Constantin-Stamate](https://github.com/Constantin-Stamate)
- Email: constantinstamate.r@gmail.com