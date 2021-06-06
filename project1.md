[Back to Portfolio](./)

# Rhino 5k Charity Race Website

- **Class: CSCI 334 (UI Programming)**
- **Grade: B**
- **Language(s): Ruby on Rails (Ruby, HTML, CSS, JavaScript, BootstrapCSS)**
- **Source Code Repository:** [lemonase/r5k](https://github.com/lemonase/r5k)
  (Please [email me](mailto:jmdixon1@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The goal of this project was to plan, prototype, design and execute a charity race website using the principles and
methods we learned throughout the semester.

On the website, Runners and Team Leaders can sign-up, add other runners, and see information related to runners and the race itself.

Our team utilized AGILE methods with user story boards, feature lists and weekly meetings.

## Running on your machine

1. Install Ruby on Rails (Ruby version 2.6.3 and Rails version 6.1.0)

1. Fork the repo and clone it:

```bash
git clone https://github.com/<username>/r5k.git
cd r5k
bundle install --without production
yarn install --check-files
```

1. Migrate the database

```bash
rails db:migrate
```

1. Run the server

```bash
rails server
```

## UI Design

In this course, we learned about the concrete and abstract elements of user interfaces
that create either a good or bad user experience and how these can be measured.

Our team focused on creating a responsive website that has all the information
one would expect on a website for such an event.

We started with a sketch and mocked up the design using MS Paint before implementing the design in code.

Leveraging the popular [Bootstrap](https://getbootstrap.com/) CSS library for the frontend and the Ruby on Rails tutorial for the backend, we
were able to get a minimum viable product by iterating on our initial design.

The result: a functional website and a design that was more refined than our prototypes.

![screenshot](images/dummy_thumbnail.jpg)
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

This project was really good experience from a project management perspective as each member of the team had the opportunity to create goals(stories), due dates and contribute to the final product.
It also provided exposure to developer tools such as [Ruby on Rails](https://rubyonrails.org/), [Heroku](https://www.heroku.com/), AWS Cloud9, Linux, git and bash.

[Back to Portfolio](./)
