import React from 'react';
import { Text, View, StyleSheet, TouchableOpacity } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text style={styles.welcomeText}>Selamat datang di</Text>
      <Text style={styles.brandText}>AyoBlajar!</Text>
      <View style={styles.logoContainer}>
        <Text style={styles.logo}>📖</Text>
      </View>
      <Text style={styles.subtitle}>
        Kejar kampus impian mu dengan belajar bersama <Text style={styles.bold}>AyoBlajar</Text>
      </Text>
      <View style={styles.buttonContainer}>
        <TouchableOpacity style={styles.button}>
          <Text style={styles.buttonText}>Masuk</Text>
        </TouchableOpacity>
        <TouchableOpacity style={[styles.button, styles.registerButton]}>
          <Text style={styles.buttonText}>Daftar</Text>
        </TouchableOpacity>
      </View>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#14124F',
    alignItems: 'center',
    justifyContent: 'center',
    padding: 20,
  },
  welcomeText: {
    color: 'white',
    fontSize: 18,
    fontWeight: '400',
  },
  brandText: {
    color: 'white',
    fontSize: 26,
    fontWeight: 'bold',
  },
  logoContainer: {
    marginVertical: 20,
  },
  logo: {
    fontSize: 40,
  },
  subtitle: {
    color: 'white',
    fontSize: 14,
    textAlign: 'center',
    marginVertical: 20,
  },
  bold: {
    fontWeight: 'bold',
  },
  buttonContainer: {
    flexDirection: 'row',
    gap: 10,
  },
  button: {
    backgroundColor: '#F7A600',
    paddingVertical: 10,
    paddingHorizontal: 30,
    borderRadius: 10,
  },
  buttonText: {
    color: 'black',
    fontWeight: 'bold',
    fontSize: 16,
  },
  registerButton: {
    backgroundColor: '#F7A600',
  },
});
