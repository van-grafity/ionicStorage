# ionicStorage
initial storage

add new page ionic start nameProject blank

1. Buka terminal, ketikkan perintah berikut :
ionic cordova plugin add cordova-sqlite-storage
npm install --save @ionic/storage

2. Buka file src/app/app.module.ts, kemudian deklarasikan storage
import { IonicStorageModule } from '@ionic/storage';

import: [IonicStorageModule.forRoot()]

