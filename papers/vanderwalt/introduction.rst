:author: Stéfan van der Walt
:email: stefan@sun.ac.za
:institution: Stellenbosch University

:author: Jarrod Millman
:email: millman@berkeley.edu
:department: Helen Wills Neuroscience Institute
:institution: University of California, Berkeley

---------
Editorial
---------

Welcome to the proceedings of the 9th Python in Science conference (SciPy2010),
held in Austin, Texas from June 28th to July 3rd 2010.

Since its inception, the conference was held at the California Institute of
Technology, but with Enthought taking a leading role in its organisation, it
made sense to move it to Austin, Texas.  We thank our colleagues and
co-organisers at CalTech for all their support and effort over the past 7
years, and for playing such an integral part in establishing this event.

What started as a small, informal meeting has now become a world-wide series of
conferences, with the third EuroSciPy held at the Ecole Normale Supérieure in Paris
from July 8th to the 11th as well as the second SciPy India in Hyderabad, Andra
Pradesh from December 13th to 18th. 

This is the third publication of a SciPy conference proceedings.

The publication of this year's proceedings was delayed due to a complete
rewrite of the publication framework.  The new framework is much easier to use
and extend and will enable us to publish future editions much more rapidly. The
tools used to produce this document are made available under an open source
license, and may be obtained from the code repository at
https://github.com/scipy/scipy-proceedings.

Conference overview
-------------------

This year's conference was attended by 187 participants from both academia and
industry.

SciPy attendees come from far and wide, including North America, Columbia,
Spain, South Africa, Turkey, Germany, Norway, Italy, Singapore and Great
Britain.

- transitions and maturity theme

Specialized tracks for this year's conference include Python for
Bioinformatics as well as Parallel Processing and Cloud Computing with Python. 

- keynotes

  - Python Concurrency, David Beazley
  - Moving Forward from the Last Decade of SciPy, Travis Oliphant

- major theme:  parallel computing and GPUs

  - tutorials

    - Brian Granger. High Performance & Parallel Computing
      mulitiple libraries: multiprocessing, mpi2py, pyzmq, IPython
    - Andreas Klockner. GPUs and Python: PyCuda, PyOpenCL

  - keynote

    - David Beazley. Python Concurrency

  - general session

    - Theano: Transparent GPU computing
      Bergstra et al.

    - Simple, Fast Messaging in Python with 0MQ and PyZMQ

  - special track: parallel

- minor theme: stat and stat data structure

  - general session

    - statsmodel, seabold
    - pandas, wes mckinney

  - BoF on datarray

  - sprints

    - added tests to scipy.stats
    - preliminary n-dimensional contingency table model w/ tests
    - scipy.stats distributions refactor
    - scikits.learn

- minor theme: astronomy

  - greenfield, aldcroft, morley, allen

- need to highlight a few articles and organize the order of articles and
  explain that organization here

- students:

  # of countries/continents, total #

::

    Elaine Angelo, Harvard University | Boston, Massachusetts
    James Bergstra, University of Montreal | Montreal, Canada
    Kadambari Devarajan, University of Illinois | Chicago, Illinois
    Gerardo Gutierrez, Universidad de Antioquia | Medellin, Colombia
    Ryan May, University of Oklahoma | Norman, Oklahoma
    Kristopher Overholt, University of Texas | Austin, Texas
    Fabian Pedregosa | University of Granada
    Nicolas Pinto, M.I.T. | Boston, Massachusetts
    Skipper Seabold, American University | Washington, D.C.
    Kurt Smith, University of Wisconsin | Madison, Wisconsin
    Stéfan van der Walt, University of Stellenbosch | Stellenbosch, South Africa
    David Warde Farley, University of Toronto | Toronto, Canada
    Omar Andres Zapata Mesa, Universidad de Antioquia | Medellin, Colombia

Review and selection process
----------------------------

Each of the 33 submitted abstracts was reviewed by both the program chairs and
two additional members of the program committee. The committee consisted of 11
members from 6 countries, and represented both industry and academia.

Abstracts were evaluated according to the following criteria:
applicability, novelty, and general impression.

We accepted 32 submissions for oral presentation at the conference. At the end
of the conference, we invited the presenters to submit their work for
publication in the proceedings. These submissions were reviewed by 14
proceedings reviewers from 8 countries.  Each reviewer provided an overall
score for each reviewed paper, based on the quality of approach and writing.
Reviewers were also asked to provide more specific feedback to the following
questions:

- Is the code made publicly available and does the article sufficiently
  describe how to access it?  We aim not to publish papers that essentially
  advertise propetiary software.  Therefore, if the code is not publicly
  available, please provide a one- to two- sentence response to each of the
  following questions: 

  - Does the article focus on a topic other than the features
    of the software itself?
  - Can the majority of statements made be externally validated
    (i.e., without the use of the software)?
  - Is the information presented of interest to readers other than
    those at whom the software is aimed?
  - Is there any other aspect of the article that would
    justify including it despite the fact that the code
    isn't available?
  - Does the article discuss the reasons the software is closed?
   
- Does the article present the problem in an appropriate context?
  Specifically, does it:
  
  - explain why the problem is important,
  - describe in which situations it arises,
  - outline relevant previous work, 
  - provide background information for non-experts 

- Is the content of the paper accessible to a computational scientist
  with no specific knowledge in the given field?

- Does the paper describe a well-formulated scientific or technical
  achievement?

- Are the technical and scientific decisions well-motivated and
  clearly explained?

- Are the code examples (if any) sound, clear, and well-written?

- Is the paper factually correct?

- Is the language and grammar of sufficient quality?

- Are the conclusions justified?

- Is prior work properly and fully cited?

- Should any part of the article be shortened or expanded? Please explain.

- In your view, is the paper fit for publication in the conference proceedings?
  Please suggest specific improvements and indicate whether you think the
  article needs a significant rewrite (rather than a minor revision).
 
----------

A conference the size of SciPy is only possible through the hard work and
dedication of a large number of volunteers.  Once again Enthought, Inc.
provided significant administrative support.  In particular, we would like to
thank Amenity Applewhite, Jodi Havranek, and Leah Jones, who not only carried a
significant administrative burden, but also did the enormous footwork required
in seeking out a location, negotating vendor prices, etc. after the conference
moved from CalTech to Austin this year.

We thank Enthought, Dell, Microsoft, D.E. Shaw & Co., AQR Financial Management,
the Python Software Foundation, and one anonymous donor, for funding 14
students to travel and attend SciPy 2010.  We also acknowledge our media
sponsor, the IEEE/AIP Computing in Science and Engineering magazine, for
publicizing the conference and providing magazines to participants.

These proceedings are the result of many hours of work by authors and reviewers
alike.  We thank them for their significant investment in these manuscripts.
The names of all contributers are listed in the "Organization" section, which
forms part of the cover material.

