# NAME

ToolSet::Math - Bring in common math functions and constants.

# SYNOPSIS

    use ToolSet::Math;

is equivalent to:

    use List::Util qw(max min sum sum0);
    use Math::Trig;
    use Math::Complex;
    use Math::Complex ":pi";
    use POSIX qw(ceil floor modf pow round isfinite isinf isnan);

Also, several constants are defined as well:

    E LN2 LN10
    PI PI2 PI4 PIP2 PIP4
    SQRT2 SQRT5 SQRT1_2 GOLDENR
    Inf nan NaN NAN
    FLT_EPSILON DBL_EPSILON

In addition, two functions are automatically exported: `log2` for base-2 logarithm, and `fac` for factorial.

# DESCRIPTION

This module automatically exports convenience math functions and constants which are not available by default in Perl, such as `ceil`, `floor`, `round`, `log10` and trigonometric ones like `tan`, `asin`, `cosec`, and `deg2rad`. It also sets up support for complex numbers to expand Perl's math capabilities.

See `Math::Trig` and `Math::Complex` for details on all exported functions.

# AUTHOR

Gerald Lai <glai@cpan.org>

# COPYRIGHT

Copyright 2021- Gerald Lai

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
