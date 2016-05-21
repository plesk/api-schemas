# Plesk XML-RPC Schemes Visualization

[View on GitHub Pages](http://plesk.github.io/api-schemas/)

Interactive diagrams for XML-RPC schemes are generated by XSDVi.

Download [XSDVi](http://xsdvi.sourceforge.net/xsdvi-20080430-1405.zip) and run:

    wget http://xsdvi.sourceforge.net/xsdvi-20080430-1405.zip
    unzip xsdvi-20080430-1405.zip -d xsdvi
    java -jar xsdvi/lib/xsdvi.jar /path/to/schema/agent_input.xsd -embodyStyle
    java -jar xsdvi/lib/xsdvi.jar /path/to/schema/agent_output.xsd -embodyStyle
    patch -p0 < agent-collapse-nodes.patch


The files `agent_input.svg` and `agent_output.svg` will be generated in the current directory.

