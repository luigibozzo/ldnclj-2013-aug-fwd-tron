# London Forward Clojure Dojo - August 2013 - Tron

A Tron Light Cycle amphitheatre.. the strategy is up to you.  In the future video game battles will be a matter of life or death.

This code was kindly donated by the good folks of http://lambdanext.eu clojure training

Thankyou to Sam Aaron, Christophe Grand, Edmund Jackson, Meikel Brandmeyer

## Usage

Implement a function in bots.clj similar to buzz.clj

Start a battle in the repl with

    (require '[tron.core :as tron])
    (use '[tron.bots])
    (tron/spawn-biker buzz)

Stop the play

    (tron/stop!)

Reset the amphitheatre

    (tron/blank-arena)

## License

Distributed under the Eclipse Public License, the same as Clojure.
