
Vagrant.configure("2") do |config|
  
  config.vm.box = "ubuntu/xenial64"
  config.vm.hostname = "pablo-couce-garcia"

  config.vm.provision "shell", inline: <<-SHELL

    echo "-- Insertar datos de ejemplo en la tabla 'libros' " > /home/vagrant/libros.sql
    echo "INSERT INTO gestion_libreria.libros (titulo, autor, ania_publicacion, genero, precio) VALUES" >> /home/vagrant/libros.sql
    echo "('Cien Años de Soledad', "Gabriel García Marquez", 1605, 'Novela', 12.99)," >> /home/vagrant/libros.sql
    echo "('Cien Años de Soledad', "Gabriel García Marquez", 1605, 'Novela', 12.99)," >> /home/vagrant/libros.sql
    echo "('Cien Años de Soledad', "Gabriel García Marquez", 1605, 'Novela', 12.99)," >> /home/vagrant/libros.sql
    echo "('Cien Años de Soledad', "Gabriel García Marquez", 1605, 'Novela', 12.99)" >> /home/vagrant/libros.sql


  SHELL

end
