# learn_spark_java

# install eclipse
- sudo mv Downloads/eclipse-standard-kepler-SR2-linux-gtk-x86_64.tar.gz /opt/ (after download eclipse)
- cd /opt
- sudo tar -xvf eclipse-standard-kepler-SR2-linux-gtk-x86_64.tar.gz
- gedit ~/.local/share/applications/eclipse.desktop
 ~ input this file on gedit
 [Desktop Entry]
  Name=Eclipse
  Type=Application
  Exec=/opt/eclipse/eclipse
  Terminal=false
  Icon=/opt/eclipse/icon.xpm
  Comment=Integrated Development Environment
  NoDisplay=false
  Categories=Development;IDE;
  Name[en]=eclipse.desktop

- nautilus ~/.local/share/applications
- and drop-down icon on desktop


# How to run psyspark, ipython with python3....Damn

- PYSPARK_PYTHON=python3 PYSPARK_DRIVER_PYTHON=ipython ./bin/pyspark
- PYSPARK_PYTHON=python3 PYSPARK_DRIVER_PYTHON=ipython PYSPARK_DRIVER_PYTHON_OPTS="notebook" ./bin/pyspark
