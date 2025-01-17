<pre><code>$ <b>module av 2>\&1 | more</b>
------------- /apps/antwerpen/modules/hopper/2015a/all ------------
ABINIT/7.10.2-intel-2015a
ADF/2014.05
Advisor/2015_update1
Bison/3.0.4-intel-2015a
Boost/1.57.0-foss-2015a-Python-2.7.9
Boost/1.57.0-intel-2015a-Python-2.7.9
bzip2/1.0.6-foss-2015a
bzip2/1.0.6-intel-2015a
...
</code></pre>

Or when you want to check whether some specific software, some compiler
or some application (e.g., LAMMPS) is installed on the {{hpc}}.

<pre><code>$ <b>module av 2>\&1 | grep -i -e "LAMMPS"</b>
LAMMPS/9Dec14-intel-2015a
LAMMPS/30Oct14-intel-2014a
LAMMPS/5Sep14-intel-2014a
</code></pre>

As you are not aware of the capitals letters in the module name, we
looked for a case-insensitive name with the "-i" option.
