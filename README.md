# DBIx-Class-Helper-ResultSet-BooleanMethods

This module automatically creates search method helpers for boolean columns.

In your ResultSet class, add:

    use Role::Tiny::With qw(with);
    use DBIx::Class::Helper::ResultSet::BooleanMethods;

    with(BooleanMethods(__PACKAGE__));

# INSTALLATION

To install this module, run the following commands:

	perl Makefile.PL
	make
	make test
	make install

# SUPPORT AND DOCUMENTATION

After installing, you can find documentation for this module with the
perldoc command.

    perldoc DBIx::Class::Helper::ResultSet::BooleanMethods

You can also look for information at:

* RT, CPAN's request tracker (report bugs here)
  * https://rt.cpan.org/NoAuth/Bugs.html?Dist=DBIx-Class-Helper-ResultSet-BooleanMethods
* AnnoCPAN, Annotated CPAN documentation
  * http://annocpan.org/dist/DBIx-Class-Helper-ResultSet-BooleanMethods
* CPAN Ratings
  * https://cpanratings.perl.org/d/DBIx-Class-Helper-ResultSet-BooleanMethods
* Search CPAN
  * https://metacpan.org/release/DBIx-Class-Helper-ResultSet-BooleanMethods

# LICENSE AND COPYRIGHT

This software is Copyright (c) 2019 by Mathieu Arnold.

This is free software, licensed under:

  The Artistic License 2.0 (GPL Compatible)

