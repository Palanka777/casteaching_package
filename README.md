# casteaching_package

# Instal·lació

```bash 
npm install @palanka777/casteaching_palanka
o
npm install @acacha/casteaching
``` 

# Usage

```javascript

import casteaching from '@acacha/casteaching'
//import casteaching from '@palanka777/casteaching_palanka'

// Obtenir llista de vídeos publicats
casteaching.videos()

// Obtenir vídeo per ID
casteaching.video.show(1)

// Crear video
casteaching.video.create({name: 'PHP 101', description: 'Bla bla bla',  url: 'https://youtube.com/...' })

// Update video
casteaching.video.update(1,{name: 'PHP 101', description: 'Bla bla bla',  url: 'https://youtube.com/...' })

// Destroy
casteaching.video.destroy(1)
```

# Author

David Pont & Sergi Tur Badenas

# More info
- https://github.com/palanka777/casteaching_palanka
- https://github.com/palanka777/casteaching_package

# Creació de repositori propi

- Scoped packages -> Prefix/espai de noms, evitar conflictes de noms -> @acacha/casteaching
- Moure a un repositori a part
- Actualitzar README
- Github submodules
