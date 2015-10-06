Java WordNet Similarity v1.0.1
Copyright (C) 2006-2007, The University of Sheffield
Copyright (C) 2011-2012, Mark A. Greenwood
Developed by Mark A. Greenwood <m.greenwood@dcs.shef.ac.uk>

=======================================================================
COPYRIGHT AND WARRANTY INFORMATION
=======================================================================

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation; either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.


=======================================================================
DESCRIPTION
=======================================================================

This library contains pure Java implementations of a number of well
known WordNet based similarity measures. It was developed as an
alternative to the popular perl WordNet::Similarity package and should
produce identical results. See the JavaDoc files for more information.

=======================================================================
OBTAINING THE SOFTWARE
=======================================================================

This library is available by following the appropriate links from
    http://nlp.shef.ac.uk/result/software.html


=======================================================================
SOFTWARE REQUIREMENTS
=======================================================================

Other than this library you will need to have installed a copy of
WordNet. I'd currently suggest installing v2.0 as Information Content
files which are required for some of the measures are available for
this version (see http://www.d.umn.edu/~tpederse/similarity.html).
Once WordNet is installed you will need to edit the wordnet.xml file
in the test directory to contain the correct install path before
testing the library, which can be done by running ant test from the
main directory of the library.
