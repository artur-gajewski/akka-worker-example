# Akka worker example

This example contain an Actor that listens to incoming processes and distributes them into ten different workers in Round-robin fashion.

## Usage

    $ sbt run