# ReactNative_imageApp

# cli

   $npm run web
   
# CodeBase

// App.js

    import * as React from 'react';
    import { Text, View, StyleSheet } from 'react-native';
    import Constants from 'expo-constants';

    // You can import from local files
    import Poupou from './components/Image';

    // or any pure javascript modules available in npm
    import { Card } from 'react-native-paper';

    export default function App() {
      return (
        <View style={styles.container}>
          <Text style={styles.paragraph}>
          </Text>
          <Card>
            <Poupou />
          </Card>
        </View>
      );
    }
    
    const styles = StyleSheet.create({
     container: {

     },
     paragraph: {

     },
    });
    
 // {Poupou}
 
      import * as React from 'react';
      import { Text, View, StyleSheet, Image } from 'react-native';

      export default function Poupou() {
        return (
          <View style={styles.container}>
            <Text style={styles.paragraph}>
               my Poupou Cat
            </Text>
            <Image style={styles.logo} source={require('../assets/poupou.png')} />
          </View>
        );
      }

      const styles = StyleSheet.create({
        container: {

        },
        paragraph: {

        },
        logo: {

        }
      });

/assets/poupou.png

  https://github.com/QueenieCplusplus/ReactNative_imageApp/tree/master/assets
  
  
  # Image with W3 Css Style
  
  add <link src/> to public/index.html 
  
  add render div to compoent (class or func)
  
  demo : see UIapp and start app in web browsing http://localhost:3001/ks-w3css

