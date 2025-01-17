<pre><code>$ <b>module av 2>\&1 | more</b>
--- /apps/gent/SL6/sandybridge/modules/all ---
ABAQUS/6.12.1-linux-x86_64
AMOS/3.1.0-ictce-4.0.10
ant/1.9.0-Java-1.7.0_40
ASE/3.6.0.2515-ictce-4.1.13-Python-2.7.3
ASE/3.6.0.2515-ictce-5.5.0-Python-2.7.6
...
</code></pre>

Or when you want to check whether some specific software, some compiler or some
application (e.g., MATLAB) is installed on the {{hpc}}.

<pre><code>$ <b>module av 2>\&1 | grep -i -e "matlab"</b>
MATLAB/2010b
MATLAB/2012b
MATLAB/2013b
</code></pre>

As you are not aware of the capitals letters in the module name, we looked for
a case-insensitive name with the "-i" option.