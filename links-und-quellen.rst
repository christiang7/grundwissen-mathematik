.. _Links und Quellen:

Links und Quellen
=================

.. _Mathe-Software:

Mathe-Software
--------------

.. index:: Computer-Algebra-System
.. _CAS:
.. _Computer-Algebra-Systeme:

.. rubric:: Computer-Algebra-Systeme


.. _Sympy:

* `Sympy <http://www.sympy.org>`__

  Sympy steht für "Symbolic Python" und bietet ein Computer-Algebra-System, das
  in die Programmiersprache :ref:`Python <gwip:Grundkurs Python 3>` eingebunden
  ist. Wer Python-Syntax kennt, findet sich also sehr schnell mit Sympy zurecht.

  Sympy hat einen erheblichen Funktionsumfang. Es kann beispielsweise Terme
  vereinfachen und vielerlei Arten von Gleichungen und Gleichungssystemen lösen;
  zudem kann Sympy unmittelbar mit der Matplotlib, dem bekanntesten
  Funktionenplotter in Python, kombiniert werden, um Lösungen als Diagramme
  darzustellen.

  Sympy wird auch für das Erstellen der Grund-Wissen-Seite genutzt; dort findet
  sich inzwischen auch ein kurzes :ref:`Sympy-Tutorial <gwip:Sympy>`.

.. _Maxima:

* `Maxima <https://wiki.ubuntuusers.de/Maxima>`__

  Maxima ist ein einfach zu erlernendes Computer-Algebra-System, das häufig als
  Lehr- und Lernplattform Anwendung findet.

  Unter Debian/Ubuntu/LinuxMint lässt sich Maxima einfach über folgendes Paket
  installieren:

  .. code-block:: bash

      sudo aptitude install wxmaxima

  Anschließend kann ``wxMaxima`` als graphische Oberfläche über einen Eintrag im
  Startmenü beziehungsweise einen Anwendungsstarter (``F2``) aufgerufen werden. Als
  textbasiertes Programm kann in einer Shell ``maxima`` aufgerufen werden.

  Zu Maxima existieren im deutschsprachigen Raum u.a. eine `Einführung (PDF)
  <http://maxima.sourceforge.net/docs/tutorial/de/maxima-einfuehrung.pdf>`_, ein
  `Workshop <http://www.austromath.at/daten/maxima/>`_ und eine ausführliche
  `Dokumentation <http://www.crategus.com/books/maxima/maxima.html>`_, die
  jeweils auch für einen schnellen Einstieg geeignet sind. Zusätzlich gibt es
  ein empfehlenswertes `Maxima-Weblog <http://casmaxima.blogspot.de/>`_, mit
  zahlreichen Anwendungs-Beispielen.

..  http://math-blog.com/2007/06/04/a-10-minute-tutorial-for-solving-math-problems-with-maxima/

.. _Sage:

* `Sage <https://wiki.ubuntuusers.de/SAGE>`__

  Sage ist ein riesiges Software-Projekt (rund 2 Gigabyte!) mit dem Ziel, eine
  Vielzahl an mathematischen Funktionalitäten zu vereinen. Auf der
  `Sage-Projektseite
  <http://doc.sagemath.org/html/en/installation/binary.html#linux-and-os-x>`_
  gibt es vorkompilierte Pakete als Downloads.

  Unter Debian/Ubuntu/LinuxMint lässt sich Sage auch über folgende
  Installationsroutine installieren:

  .. code-block:: bash

      sudo add-apt-repository ppa:aims/sagemath
      sudo apt-get update
      sudo apt-get install sagemath-upstream-binary

  Anschließend kann Sage über einen Eintrag im Startmenü, oder über die Eingabe
  von ``sage`` in einem Anwendungsstarter (``F2``) oder einer Shell gestartet
  werden. Eine entsprechend ausführliche, englischsprachige Dokumentation findet
  sich als `Reference Manual <http://www.sagemath.org/doc/reference/>`_ ebenfalls
  auf der Projektseite.

.. index:: Funktionen-Plotter
.. _Funktions-Plotter:
.. _Funktionen-Plotter:

.. rubric:: Funktionen-Plotter

Viele Mathematik-Programme haben bereits einen Funktionenplotter in der Software
integriert. Zusätzlich gibt es (skriptbare) Funktionenplotter, die wahlweise
direkt als Interpreter genutzt werden können oder als Skriptsprache von anderen
Programmen genutzt werden können.


.. _Matplotlib:

* `Matplotlib <http://matplotlib.org/index.html>`__

  Die Matplotlib ist eine Codebibliothek für die Programmiersprache Python. Sie
  kann von Interpretern wie `IPython <https://ipython.org/>`_ aus aufgerufen
  oder kann von anderen in Python geschriebenen Werkzeugen (insbesondere auch in
  `Sphinx-Dokumentationen
  <http://matplotlib.org/sampledoc/extensions.html#inserting-matplotlib-plots>`_)
  genutzt werden.

  Unter Debian/Ubuntu/LinuxMint lässt sich die Matplotlib auf folgende Weise
  installieren:

  .. code-block:: bash

      sudo aptitude install ipython3 python3-setuptools
      sudo pip3 matplotlib

  Anschließend können durch den Aufruf von ``ipythone -pylab`` in einer Shell die
  Funktionen der Matplotlib sowie weitere numerische Funktionen direkt über den
  Interpreter genutzt werden. Hierzu gibt es u.a. ein gelungenes
  `Einstiegs-Tutorial
  <http://www.pro-linux.de/artikel/2/168/matplotlib-und-pylab.html>`_ und ein
  weiteres `Tutorial mit bunten Bildchen
  <http://scienceblogs.de/diaxs-rake/2009/04/09/wissenschaftliches-arbeiten-mit-python-und-pylab-ii-bunte-bildchen-mit-matplotlib/>`_;
  auch auf der Grund-Wissen-Seite gibt es inzwischen ein kleines
  :ref:`Matplotlib-Tutorial <gwip:matplotlib>`.


.. _Gnuplot:

* `Gnuplot <https://wiki.ubuntuusers.de/Gnuplot>`__

  Gnuplot ist weit entwickelter Funktionenplotter für 2D- und 3D-Plots, der als
  eigener Interpreter oder als Skriptsprache genutzt werden kann.

  Unter Debian/Ubuntu/LinuxMint lässt sich ``gnuplot`` einfach über folgendes
  Paket installieren:

  .. code-block:: bash

      sudo aptitude install gnuplot gnuplot-x11 gnuplot-doc

  Anschließend kann Gnuplot über einen Eintrag im Startmenü, oder über die
  Eingabe von ``gnuplot`` in einem Anwendungsstarter (``F2``) oder einer Shell
  gestartet werden.

  Zu Gnuplot gibt es u.a. eine einführende `PDF-Präsentation
  <http://blog.stud.uni-goettingen.de/julius/files/2010/03/gnuplot_2010.pdf>`_,
  ein Kurz-Tutorial
  `http://www3.physik.uni-stuttgart.de/studium/praktika/ap/pdf_dateien/Allgemeines/BeschreibungGnuplot.pdf`
  und eine englischsprachige `Kurz-Einführung
  <http://www.usm.uni-muenchen.de/people/puls/lessons/intro_general/gnuplot/gnuplot_for_beginners.pdf>`_.
  Weitere Dokumentationen und Beispiel-Plots finden sich auf der
  `Gnuplot-Projektseite <http://www.gnuplot.info/>`_.




.. _Geometrie-Software:

.. rubric:: Geometrie-Software


.. _Geogebra:

* `Geogebra <https://wiki.ubuntuusers.de/GeoGebra>`__

  Geogebra ist ein Programm zur Konstruktion und Auswertung geometrischer von
  Konstruktionen. Die erstellten Zeichnungen können in einer Vielzahl an
  Formaten, u.a. PDF, PNG und SVG, ausgegeben werden.

  Unter Debian/Ubuntu/LinuxMint lässt sich Geogebra einfach über folgendes
  Paket installieren:

  .. code-block:: bash

      sudo aptitude install geogebra

  Anschließend kann Geogebra über einen Eintrag im Startmenü, oder über die
  Eingabe von ``geogebra`` in einem Anwendungsstarter (``F2``) oder einer Shell
  gestartet werden.

  Zu Geogebra existiert ein umfangreiches `Wiki (de)
  <https://wiki.geogebra.org/de/Hauptseite>`_, das neben Tutorials, Tipps und
  Tricks auch ein deutschsprachiges `Handbuch
  <https://wiki.geogebra.org/de/Handbuch>`_ enthält.


.. _Simulatoren:
.. _Simulations-Werkzeuge:

.. rubric:: Simulations-Werkzeuge


.. _Scilab:

* `Scilab <https://wiki.ubuntuusers.de/Scilab>`__

  Unter Debian/Ubuntu/LinuxMint lässt sich Scilab einfach über folgendes Paket
  installieren:

  .. code-block:: bash

      sudo aptitude install scilab

  Anschließend kann Scilab über einen Eintrag im Startmenü, oder über die
  Eingabe von ``scilab`` in einem Anwendungsstarter (``F2``) oder einer Shell
  gestartet werden.

  Zu Scilab gibt es im deutschsprachigen Bereich neben mehreren kommerziellen
  Büchern auch Anleitungen (zu etwas fortgeschrittenen Anwendungen) als
  PDF-Dateien, und zwar  `hier
  <http://alexanderstoffel.selfip.org/scimat/scilabein.pdf>`__, `hier
  <http://zogg-jm.ch/Dateien/Arbeiten%20mit%20Scilab%20und%20Scicos_v1.pdf>`__
  und `hier <http://homepage.univie.ac.at/scharif.purhassan/sda/PinconD.pdf>`__.

  Umfangreiche, englischsprachige Dokumentationen finden sich auf der
  `Scilab-Projektseite <http://www.scilab.org/scilab/features>`_ sowie in den internen
  Hilfe-Seiten, die sich mittels des Pakets ``scilab-doc`` installieren lassen.


.. _Octave:

* `Octave <https://wiki.ubuntuusers.de/Octave>`__

  Unter Debian/Ubuntu/LinuxMint lässt sich Octave einfach über folgendes Paket
  installieren:

  .. code-block:: bash

      sudo aptitude install octave3.2

  Zusätzlich ist eine Installation der Pakete ``gnuplot`` und ``octave-epstk``
  als Funktionenplotter sinnvoll. Anschließend kann Octave über einen Eintrag im
  Startmenü oder über die Eingabe von ``octave`` in einem Anwendungsstarter
  (``F2``) oder einer Shell gestartet werden.


  Zu Octave gibt es im deutschsprachigen Raum mehrere Tutorials, u.a. `hier
  <http://www.christianherta.de/octaveMatlabTutorial.php>`_. Eine komplette,
  englischsprachige Dokumentation existiert als `Online-Handbuch
  <https://www.gnu.org/software/octave/doc/interpreter/index.html>`_ oder
  `PDF-Version <https://www.gnu.org/software/octave/octave.pdf>`_.


.. _Statistik-Software:

.. rubric:: Statistik-Software

.. _Gnumeric:

* `Gnumeric <https://wiki.ubuntuusers.de/Gnumeric>`__

  Gnumeric ist als Tabelleneditor eine schlanke Alternative zum
  Tabellenkalkulationsprogramm `Calc
  <https://wiki.ubuntuusers.de/Office_Komponenten#Calc-Tabellenkalkulation>`_ von
  LibreOffice. Neben vielen Import- und Export-Funktionen verfügt es auch über
  statistische Funktionen und einen integrierten Funktionenplotter.

  Unter Debian/Ubuntu/LinuxMint lässt sich Gnumeric einfach über folgendes Paket
  installieren:

  .. code-block:: bash

      sudo aptitude install gnumeric

  Anschließend kann Gnumeric über einen Eintrag im Startmenü, oder über die
  Eingabe von ``gnumeric`` in einem Anwendungsstarter (``F2``) oder einer Shell
  gestartet werden.

  Die graphische Benutzeroberfläche ist weitestgehend selbsterklärend.
  Dokumentationen gibt es im Bereich :`Grund-Wissen Linux <gwl:Gnumeric>`, unter
  den integrierten Hilfeseiten sowie in englischsprachiger Form auf der
  `Gnumeric-Projektseite <http://gnumeric.org/>`_.

.. _R:

* `R <https://wiki.ubuntuusers.de/R>`__

  ``R`` ist eine Interpreter-Software für statistische Funktionen und gleichzeitig
  eine skriptbare Programmiersprache. Im wissenschaftlichen Bereich hat sich R
  in den letzten Jahren zunehmend als Standard-Werkzeug für statistische
  Analysen etabliert.

  Unter Debian/Ubuntu/LinuxMint lässt sich ``R`` einfach über folgendes
  Paket installieren:

  .. code-block:: bash

      sudo aptitude install r-base r-recommended

  Anschließend kann R in einer Shell mittels ``R`` aufgerufen werden. Als
  graphische Bedienoberfläche kann beispielsweise das Paket ``rkward``
  zusätzlich installiert werden.

  Als Dokumentationen gibt es ein `Wikibook
  <https://upload.wikimedia.org/wikibooks/de/4/47/GNU_R.pdf>`_ sowie zum
  Einstieg eine `Einführung in R
  <https://cran.r-project.org/doc/contrib/Sawitzki-Einfuehrung.pdf>`_ und einen
  `R Reader <https://cran.r-project.org/doc/contrib/Grosz+Peters-R-Reader.pdf>`_
  als PDF-Dateien. Weitere Dokumentationen in anderen Sprachen sind in einer
  `Manual-Liste <https://cran.r-project.org/other-docs.html#nenglish>`_
  aufgeführt. Auf der `R-Projektseite <https://cran.r-project.org/>`_ ist
  zusätzlich eine Vielzahl an Erweiterungen mitsamt Beschreibungen zu finden.

  Inzwischen gibt es weitgehenden Nachbau von ``R`` in der Programmiersprache
  Python -- dieses Projekt heißt :ref:`Pandas <gwip:Pandas>`. Wer also auf die
  Funktionalitäten von ``R`` zurückgreifen, aber keine extra Programmiersprache
  lernen möchte, wird hiermit gut beraten sein..


.. _Links:

Links
-----

.. _Youtube-Videos:

.. rubric:: Youtube-Videos

* `Mathe-Videos von "Educational Videos and Lectures" <https://www.youtube.com/playlist?list=PLdId9dvaMGZNfU-Xg8fwOw_3sTpSygluy>`__



.. rubric:: Diverses

* `Mathematik-Wikipedia <http://de.academic.ru/dic.nsf/dewiki/928928>`_
* `Online-Mathe-Lexikon <http://www.computermathematik.info/>`_
* `Online-Mathebuch "Mathe 1" <http://www.mathe1.de/>`_
* `Mathematik -- Erste Hilfe <https://www.mathematik.de/erstehilfe>`_
* `Mathematischer Vorkurs zum Physik-Studium (pdf) <http://www.thphys.uni-heidelberg.de/~hefft/vk_download/vk1.pdf>`_
* `Mathematische Basteleien <http://www.mathematische-basteleien.de/>`_

.. `Mathestunde <https://www.mathestunde.com/>`_
..  * `Mathematik-Blog von Sean Bohum (en.) <http://www.seanmathmodelguy.com/>`_

.. rubric:: Weiterführende Mathematik

* `FH-Lehrmaterialien Mathematik von Alexander Stoffel <http://alexanderstoffel.selfip.org/lehrmat.html>`_

.. _Quellen:

Quellen
-------

.. <h2>Quellen<a class="headerlink" href="#quellen" title="Permalink zu dieser Überschrift"></a></h2>

.. rubric:: Quellenangaben zur Logik

Der strukturelle Aufbau dieses Abschnitts orientiert sich an [Simon1980]_ (Seite
33 ff). Ähnliche inhaltliche Zusammenfassungen sind in vielerlei Fachbüchern zu
finden.

..

.. Induktionsbeweis Summenformel: Walz2010 S. 47

.. rubric:: Quellenangaben zur Mengenlehre

Die strukturellen Vorlagen für diesen Abschnitt stammen aus [Simon1980]_ (Seite
57 ff) sowie [Voelkel1991]_ (Seite 15 ff).

.. rubric:: Quellenangaben zu Arithmetik

Im Abschnitt :ref:`Folgen und Reihen <Folgen und Reihen>` wurden mehrere
fachliche Ergänzungen von [Simon1980]_ (Seite 448 ff.) und [Bewert1971]_ (Seite
183 ff.) aufgegriffen. Die Hinweise auf den rechnerischen Umgang mit dem
Summenzeichen sind inhaltlich an [Cramer2009]_ (Seite 116) angelehnt. Der Beweis
zur Auswertungsformel für geometrische Reihen ist aus [Simon1980]_ (Seite 459
f.) entnommen.

Die im Abschnitt :ref:`Weitere Teilbarkeitsregeln <Weitere Teilbarkeitsregeln>`
aufgeführten Regeln sind in ausführlicher Form (inklusive Beweisen) in
[Bittner1979]_ (Seite 31 ff.) zu finden.

.. Voelkel[1991]

.. Teilbarkeitsregeln: Auch Kemnitz.

.. rubric:: Quellenangaben zu elementarer Algebra

Der Beweis zum Satz des Vieta wird in ähnlicher Form [Simon1980]_ (Seiten 257f.
und 263) geführt.

.. rubric:: Quellenangaben zu elementarer Geometrie

Der Aufbau dieses Kapitels orientiert sich an [Bewert1985]_ und [Voelkel1991]_.

..  Aus Voelkel insbesondere Beweis der Euklidschen Saetze, Struktur des
..  Dreiecke-Kapitels

.. rubric:: Quellenangaben zu Stochastik

Der bisherige Aufbau dieses Abschnitts orientiert sich an [Olmscheid1994]_.


.. raw:: html

    <hr />

.. only:: html

    .. rubric:: Quellen-Liste:

.. [Bewert1971] Fritz Bewert: Lehr- und Übungsbuch Mathematik 1: Arithmetik,
    Algebra und elementare Funktionenlehre. Harri Deutsch Verlag, Frankfurt am
    Main, 1971.

.. [Bewert1985] Fritz Bewert: Lehr- und Übungsbuch Mathematik 2: Planimetrie,
    Stereometrie und Trigonometrie der Ebene. Harri Deutsch Verlag, Frankfurt am
    Main, 1985.

.. [Bewert1982] Fritz Bewert: Lehr- und Übungsbuch Mathematik 3: Analytische
    Geometrie, Vektorrechnung und Infinitesimalrechnung. Harri Deutsch Verlag,
    Frankfurt, 1982.

.. [Bittner1979] Rudolf Bittner, Dieter Ilse, Siegmar Kubicek, Werner Tietz:
    Kompendium der Mathematik. Volk und Wissen Verlag, Berlin, 1979.

.. [Cramer2009] Erhard Cramer, Johanna Neslehova: Vorkurs Mathematik. Springer
    Verlag, Berlin, 2009.

.. [Hoffmann2004] Manfred Hoffmann: Mathematik -- Formeln, Regeln und
    Merksätze. Compact Verlag, München, 2004.

.. [Mueller-Fonfara2006] Robert Müller-Fonfara und Wolfgang Scholl: Mathematik
    verständlich. Weltbild Verlag, 2006.

.. [Olmscheid1994] Werner Olmscheid: Einführung in die
    Wahrscheinlichkeitsrechnung. Softrutti Verlag, 1994.

.. [Potuntke2006] Werner Poguntke: Keine Angst vor Mathe. Teubner Verlag, 2006.

.. [Rapp2010] Heinz Rapp: Mathematik für die Fachschule Technik. Vieweg-Teubner Verlag, 2010.

.. [Simon1980] Hans Simon, Kurt Stahl und Helmut Grabowski: Taschenbuch der
    Schulmathematik. Verlag Harri Deutsch, Frankfurt am Main, 1980.

.. [Voelkel1991] Siegfried Völkel: Mathematik für Techniker. Fachbuch-Verlag
    Leipzig, 1991.

.. Biesterfeld1990] Walther Biesterfeld, Frank Schröder und Jakob Stragten:
.. Mathematik für die Fachhochschulreife. Dähmlow Verlag, 1990.

