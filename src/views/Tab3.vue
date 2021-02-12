        <template>
        <ion-page>
          <ion-header>
            <ion-toolbar>
              <ion-title>Test Components</ion-title>
            </ion-toolbar>
          </ion-header>
          <ion-content :fullscreen="true">
            <ion-header collapse="condense">
              <ion-toolbar>
                <ion-title size="large">Tab 3</ion-title>
              </ion-toolbar>
            </ion-header>
          <ion-item>
            <ion-label>Suffix</ion-label>
            <ion-select :interface-options="customActionSheetOptions" interface="action-sheet" placeholder="Suffix">
              <ion-select-option aria-label="Senior" value="Sr">Sr</ion-select-option>
              <ion-select-option aria-label="Junior" value="Jr">Jr</ion-select-option>
              <ion-select-option aria-label="The First" value="I">I</ion-select-option>
              <ion-select-option aria-label="The Sec" value="II">II</ion-select-option>
              </ion-select>
          </ion-item>
 </ion-content>
        </ion-page>
        </template>

        <script lang="ts">
        import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
        import {  IonItem, IonLabel } from '@ionic/vue';

        export default  {
        name: 'Tab3',
        components: { IonHeader, IonItem, IonToolbar,IonLabel, IonTitle, IonContent, IonPage }
        }


        </script>