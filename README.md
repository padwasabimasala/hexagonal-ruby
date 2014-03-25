hexagonal-ruby
==============

A place to discuss and experiment with Hexagonal Architecture in Ruby and Rails

## Update 2014-03-25

Collective Idea has a neat little gem for rolling up business rules into interactors. Interactors are just "use cases." They should conform to SRP, and can be linked together for multistep tasks.

The gem makes this all very easy.

https://github.com/collectiveidea/interactor

This is similar to "form objects" or resources described by Code Climate and others

http://blog.codeclimate.com/blog/2012/10/17/7-ways-to-decompose-fat-activerecord-models/



## Update 2013-07-08

Avdi Grim has a great ebook that covers this topic *VERY* well

http://objectsonrails.com/

In it he references another great article on keeping Rails models thin

http://solnic.eu/2011/08/01/making-activerecord-models-thin.html

## Core Concepts

Alistari Cockburn's page on Hexagonal Architecture

http://alistair.cockburn.us/Hexagonal+architecture

Robert Martin's talk on Architecture in Rails

http://www.confreaks.com/videos/759-rubymidwest2011-keynote-architecture-the-lost-years

Victor Savkin has a good article about combing the above concepts

http://victorsavkin.com/post/42542190528/hexagonal-architecture-for-rails-developers

# Further Reading

Obvious is a Ruby lib by RetroMocha that was inspiried by these ideas

http://obvious.retromocha.com/

Ostryalabs has an article on refactoring controllers to be Hexagonal

http://ostryalabs.com/blog/2012/11/27/hexagonal-refactoring-controller.html

Victor Savkin blogs about DCI in Ruby and here discusses decoupling your Rails models from ActiveRecord

http://victorsavkin.com/post/41016739721/building-rich-domain-models-in-rails-separating

## Some Resources for Ruby CQRS

Ruby CQRS with event sourcing

https://github.com/slashdotdash/rcqrs

Simple Presentation on CQRS in Ruby

http://holsee.com/the-cqrs-diet-presentation/

An example App in Ruby doing CQRS

https://github.com/cavalle/banksimplistic

See the comment [http://stackoverflow.com/questions/6879685/cqrs-in-a-rails-environment](here) on CQRS implementations generally having two databases.

Links from that post

http://www.cqrsinfo.com/

http://www.udidahan.com/2009/12/09/clarified-cqrs/

## Other Resources

In his talk Robert Martin recommends the book "Object-Oriented Software Engineering" 

http://www.amazon.com/Object-oriented-Software-Engineering-Approach-Press/dp/0201544350

In his talk Robert Martin mentions the Model View Presenter Pattern. Martin Fowler has more thoughts about that here.

http://martinfowler.com/eaaDev/ModelViewPresenter.html

## Footnote

Hopefully some day they'll be some code here. ٩(͡๏̯͡๏)۶
