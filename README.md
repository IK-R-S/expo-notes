
# expo-notes
_Notas de instalações e configurações básicas do expo_

## Instalando o expo em distribuições linux (Ubuntu, Debian)
```bashscript
sudo apt update
sudo apt upgrade ```y```
sudo apt install nodejs ```y```
sudo apt install npm ```y```
npm install expo-cli --global
```

## 📲️ MÓDULO DE NAVEGAÇÃO - REACT NAVIGATION ⚛️

### Instalação:

```npm install @react-navigation/native```

```expo install react-native-screens react-native-safe-area-context```

```npm install @react-navigation/native-stack```

### Importações:

```import { NavigationContainer } from '@react-navigation/native';```

```import { createNativeStackNavigator } from '@react-navigation/native-stack';```

## 📲️ MÓDULO DE DRAWER - REACT NAVIGATION ⚛️

```npm install @react-navigation/drawer```

```expo install react-native-gesture-handler react-native-reanimated```

## 📲️ MÓDULO DE TABBAR - TAB BAR NAVIGATION ⚛️

### Instalação:

```npm install @react-navigation/native``` (óbvio)

```npm install @react-navigation/bottom-tabs```

### Importações:

```import { createBottomTabNavigator } from '@react-navigation/bottom-tabs';```

## 📲️ MÓDULO DE TOP TAB - TOP TAB NAVIGATOR ⚛️

### Instalação:
```npm install @react-navigation/material-top-tabs react-native-tab-view```

```expo install react-native-pager-view```

### Importações:
```import { createMaterialTopTabNavigator } from '@react-navigation/material-top-tabs';```
