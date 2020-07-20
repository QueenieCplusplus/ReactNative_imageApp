# ReactNative_imageApp

# cli

   $npm run web


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
