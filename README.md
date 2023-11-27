# ANOTAÇOES IMPORTANTES

Para começar deve-se rodar o comando npx expo start e depois abrir no celular e apertar a no cmd para linkar os dois

No arquivo app.js é que todos elementos estejam dentro de tags, inclusive os textos que devem estar com a tag <Text>

O importe do stylesheet se faz necessario para criar um grupo de estilo sem precisar ficar usando inline

o import Touchable é m botao que o usuario podera clicar dentro do celular.

O botao para que seja ativado usa-se a propriedade onPress, que tem a mesma função do onClick no desenvolvimento web

 # Exemplo de código
  <!-- return (
    <View style={styles.container}>
      <Text style={styles.title}>Sujeito Pizzaria </Text>
      <Text>{nome}</Text>

      <TouchableOpacity style={styles.button} onPress={handleMudarNome}>
        <Text style={styles.buttonText}>Mudar nome</Text>
      </TouchableOpacity>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: "#f1f1f1",
    paddingTop: 28,
  },
  title: {
    fontSize: 32,
    color: "#121212",
    fontWeight: "bold",
    textAlign: "center",
  },
  button: {
    backgroundColor: "blue",
    height: 40,
    justifyContent: "center",
    alignItems: "center",
    marginTop: 35,
  },
  buttonText: {
    color: "#fff",
    fontWeight: "bold",
  },
}); -->

# 