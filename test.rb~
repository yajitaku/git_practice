# -*- coding: utf-8 -*-
require 'sqlite3'

db = SQLite3::Database.new "test.db"
db.results_as_hash = true

books = db.execute("SELECT title,author,price FROM books;")

p books
