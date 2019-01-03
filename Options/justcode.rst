JustCode
========
Key Goals
---------

Options
-------

Scratch
-------

KidsRuby
--------

Python
------

Hopscotch
~~~~~~~~~

Powershell
~~~~~~~~~~
The wannacookie code:

.. code-block:: powershell

    function A2H(){
        Param($a)
        $c = ''
        $b = $a.ToCharArray();
        Foreach ($element in $b) {
            $c = $c + " " + [System.String]::Format("{0:X}", [System.Convert]::ToUInt32($element))
        }
        return $c -replace ' '
    }


.. code-block:: c++

    #include<iostream>
    using namespace std;
    int main(){
        int a,b;
        cin>>a>>b;
        cout<<a+b;
        return 0;
    }