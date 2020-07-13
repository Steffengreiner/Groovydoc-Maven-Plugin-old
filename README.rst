groovydoc-maven-plugin

.. image:: https://img.shields.io/travis/qbicsoftware/groovydoc-maven-plugin.svg
        :target: https://travis-ci.org/qbicsoftware/groovydoc-maven-plugin

.. image:: https://readthedocs.org/projects/groovydoc-maven-plugin/badge/?version=latest
        :target: https://groovydoc-maven-plugin.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

.. image:: https://flat.badgen.net/dependabot/thepracticaldev/dev.to?icon=dependabot
    :alt: Dependabot Enabled


Maven plugin to allow for inclusion of Gmavenplus generated Groovydocs in project-reports.html

* Free software: MIT license
* Documentation: https://groovydoc-maven-plugin.readthedocs.io.

Features
--------


Usage
--------

To use :code:`groovydoc-maven-plugin` in a project:

:code:`groovydoc-maven-plugin` is intended as a maven plugin, that has to be included in the reporting section of the project pom.

To include groovydoc-maven-plugin in your project you'll need to add it to pom as such:

:code:`
     <reporting>
      <plugin>
        <groupId>life.qbic</groupId>
        <artifactId>groovydoc-maven-plugin</artifactId>
        <version>1.0-SNAPSHOT</version>
      </plugin>
     </plugins>
    </reporting>`

Credits
-------

This plugin is based on the report mojo tutorial by the apache maven project

.. _Maven-Mojo: https://maven.apache.org/guides/plugin/guide-java-report-plugin-development.html
