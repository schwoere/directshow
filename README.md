directshow
==========
This is the directshow Ubitrack submodule.

Description
----------
The directshow contains MS Windows specific directshow framegrabber.

Usage
-----
In order to use it, you have to clone the buildenvironment, change to the ubitrack directory and add the directshow by executing:

    git submodule add https://github.com/schwoere/directshow.git modules/directshow


Dependencies
----------
In addition, this module has to following submodule dependencies which have to be added for successful building:

<table>

  <tr>
    <th>Dependency</th><th>Dependent Components</th><th>optional Dependency</th>
  </tr>
  <tr>
    <td>utdataflow, utvision</td><td>directshow</td><td>no</td>
  </tr>
</table>
