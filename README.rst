groovydoc-maven-plugin

.. image:: https://img.shields.io/travis/qbicsoftware/groovydoc-maven-plugin.svg
        :target: https://travis-ci.org/qbicsoftware/groovydoc-maven-plugin

.. image:: https://flat.badgen.net/dependabot/thepracticaldev/dev.to?icon=dependabot
    :alt: Dependabot Enabled

Maven plugin to allow for inclusion of Gmavenplus generated Groovydocs in project-reports.html

* Free software: MIT license

Usage
--------

To use :code:`groovydoc-maven-plugin` in a project:

:code:`groovydoc-maven-plugin` is intended as a maven plugin, that has to be included in the reporting section of the project pom.

.. code-block:: xml

 <reporting>
  <plugins>
   <plugin>
    <groupId>life.qbic</groupId>
    <artifactId>groovydoc-maven-plugin</artifactId>
    <version>1.0</version>
   </plugin>
  </plugins>
 </reporting>


Credits
-------

This plugin is based on the report mojo tutorial by the apache maven project

.. _Maven-Mojo: https://maven.apache.org/guides/plugin/guide-java-report-plugin-development.html
