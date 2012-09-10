unplugged-jnlp
==============
inspired in the work done by: http://code.google.com/p/jnlpdownloader/
I plan to make it more complete adding features such as: downloading behind a proxy, using it as a Maven plugin/Ant Task, making it more configurable by allowing it to download JNLP files itself (and not just their resources), keeping original folder structure and much more, in aim to make it easier to use with NetBeans RCP applications

Public repository for unplugged JNLP. Tool that aims to make it easier to deploy Web Start applications (especialy those using the NetBeans Rich Client Platform) on environments where Internet connectivity is non existant

Work in progress! I'll be commiting most part of it next weekend.

-----
What's done:

async download of JNLP/extension files using https://github.com/sonatype/async-http-client
JNLP XML (un)marshalling using JAXB