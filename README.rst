Kate editor syntax higlighter modifications
============================================

In this file I added some simple rules that highlights some
common pep8 syntax errors like::

    ["hello","world"] # space needed after comma, red color on the comma
    {"hello":"world"} # space needed after colon, red color on the colon
    def toto(hello,world): # space needed after comma, red color on the comma
    def toto(hello = world): # space incorrect in function definition, red color on the equal sign

Plus a new attribute Separator for ":" and ","