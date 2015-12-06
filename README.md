Shorewall Configuration Files
=============================

Shorewall configuration files for shorewall multi-interface firewall with blacklist enabled.

# Installtion

<pre>
<code>

apt-get install shorewall
rm -frv /etc/shorewall
git clone git@github.com:mckinnon81/single-shorewall.git /etc/shorewall
shorewall refresh
shorewall restart

</code>
</pre>

To have shorewall start on start up

<pre>
<code>
vi /etc/default/shorewall
</code>
</pre>

Change
<pre>
<code>
startup=0
</code>
</pre>

to

<pre>
<code>
startup=1
</code>
</pre>
