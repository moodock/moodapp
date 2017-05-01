

About SUSHITOS and Moodbile
===========================

    SUSHITOS is a Research group in the Barcelona Tech (Universitat Politècnica de Catalunya UPC).

    Founded in 2009 as a Research grup in the ESSI department, nowadays SUSHITOS gathers a group of
    faculty, PHD students and researchers from several Departments and Schools of the UPC.

    SUSHITOS has been acknowledged as an emergent research group by the Generalitat de Catalunya.

    The Moodbile project aims to enable mobile learning applications and other kinds of applications
    for education to work together with the LMS. Moodbile is an open source project.  The LMS Moodle
    is used as host LMS platform in the first stage of the project. Rather than just creating mobile
    applications that replicate the LMS functionalities on a mobile device, Moodbile provides the
    developers of applications for Education with the necessary tools to interact with the LMS.

    Moodbile is a project initiated by the SUSHITOS Research Group in collaboration with the GRIAL
    Research Group of the Universidad de Salamanca <http://grial.usal.es/>.

    The motivation of the Moodbile project is to open up the most commonly used e-learning platforms
    and LMS, originally designed as monolithic or layered systems, to the service paradigm.

    This work is an interoperability solution to extend LMS to other environments such as the mobile
    world. Its aim is to contribute in adapting LMS to the current generation of e-learning 2.0. Its
    first LMS target is Moodle.

    Moodbile is Copyright 2009 by Maria Jose Casany, Marc Alier and Jordi Piguillem.

    Moodbile is released as Free Software under GNU General Purpose License v3.

    Contact info: Marc Alier at <marc.alier@upc.edu> and <http://moodbile.org>



Moodbile Android Client
=======================

- Moodbile Android Client is part of Moodbile project - <https://sushitos.upc.edu/tools/moodbile>

- Copyright 2012 Maria Jose Casany, Marc Alier, Jordi Piguillem, Nikolas Galanis <marc.alier@upc.edu>

- Copyright 2012 Universitat Politecnica de Catalunya - Barcelona Tech - <http://www.upc.edu>

- Author: Alfonso Bocanegra de Luis - <albodelu@gmail.com>

- License: <http://www.gnu.org/licenses/gpl-3.0.en.html> - [GNU GPL v3 or later](licenses/GPLv3.txt)


    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

- Dependencies: different versions include code or depend on Moodock and Moodgen libraries.


Moodgen
-------

- Moodgen is an experimental graphic library originally included in Moodbile Android Client.

- Copyright 2012 Maria Jose Casany, Marc Alier, Jordi Piguillem, Nikolas Galanis, Alfonso Bocanegra

- Copyright 2012 Universitat Politecnica de Catalunya - Barcelona Tech - <http://www.upc.edu>

- Author: Alfonso Bocanegra de Luis - <albodelu@gmail.com>

- Dual License:

    GNU LGPL v3 or later - <http://www.gnu.org/licenses/lgpl-3.0.en.html>

    Apache License, Version 2.0 - <http://www.apache.org/licenses/LICENSE-2.0>

 - Dependencies: Moodgen depends on Moodock library and includes modified NewQuickAction classes.


Moodock
-------

- Moodock is an experimental persistence library originally included in Moodbile Android Client.

- Copyright 2012 Maria Jose Casany, Marc Alier, Jordi Piguillem, Nikolas Galanis, Alfonso Bocanegra

- Copyright 2012 Universitat Politecnica de Catalunya - Barcelona Tech - <http://www.upc.edu>

- Author: Alfonso Bocanegra de Luis - <albodelu@gmail.com>

- Dual License:

    GNU LGPL v3 or later - <http://www.gnu.org/licenses/lgpl-3.0.en.html>

    Apache License, Version 2.0 - <http://www.apache.org/licenses/LICENSE-2.0>

- Dependencies: Moodock depends on third-party libraries Signpost and SLF4J for Android, see below.

    Previous versions could depend on [Roboguice](https://github.com/roboguice/roboguice) version 1
    for dependency injection, Apache License 2.0.


About Moodapp and this project version
===========================================

Moodapp is a personal project that uses and extends Moodock and Moodgen Apache License 2.0 versions.

<http://moodock.org/mood>

Moodbile Android Client is a GPL project continued after I finished my studies and work at UPC.

<http://upcommons.upc.edu/pfc/handle/2099.1/14074?locale=en>

I send them libraries updates and other authors extended it but their code is not included here.

<http://upcommons.upc.edu/pfc/simple-search?query=moodbile&submit=Go?locale=en>

I don't know their current plans or project status, please contact them for further information.

<https://sushitos.upc.edu/tools/moodbile> - <http://www.moodbile.org>

I include Moodbile here only for testing purposes and to maintain compatibility with my future work.

<http://moodock.org/moodbile>

Moodapp depends on third-party libraries, please see the respective [README file](../README.md).


Third-party libraries and licenses
==================================

Moodock
-------

- Moodock is an experimental persistence library originally included in Moodbile Android Client.

- Library: <http://moodbile.org> or <http://moodock.org/moodbile>

- License: [Apache License Version 2.0](licenses/ALv2.0.txt) or <http://www.apache.org/licenses/LICENSE-2.0>

- Usage: Included an extended version in Moodapp and used by Moodbile and other projects.

Moodgen
-------

- Moodgen is an experimental graphic library originally included in Moodbile Android Client.

- Library: <http://moodbile.org> or <http://moodock.org/moodbile>

- License: [Apache License Version 2.0](licenses/ALv2.0.txt) or <http://www.apache.org/licenses/LICENSE-2.0>

- Usage: Included an extended version in Moodapp and used by Moodbile and other projects.

NewQuickAction
--------------

- NewQuickAction is a small android library to create QuickAction dialog.

- Library: <https://github.com/lorensiuswlt/NewQuickAction>

- License: [Apache License Version 2.0](licenses/ALv2.0.txt) or <http://www.apache.org/licenses/LICENSE-2.0>

- Usage: Included modified classes in Moodgen: QuickAction, QuickActionBase and QuickActionItem.

Signpost
--------

- Signpost is a simple OAuth message signing for Java.

- Library: <https://github.com/mttkay/signpost>

- License: [Apache License Version 2.0](licenses/ALv2.0.txt) or <http://www.apache.org/licenses/LICENSE-2.0>

- Usage: Included an unmodified version in Moodock as a Gradle dependency.

SLF4J for Android
-----------------

- SLF4J for Android is a logging framework.

- Library: <http://www.slf4j.org/android>

- License: [MIT license](licenses/MITlicense.txt) or <http://opensource.org/licenses/MIT>

- Usage: Included an unmodified version in Moodock as a Gradle dependency.


