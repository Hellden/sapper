

<script>

function handleSubmitContact(){
  console.log("coucou")
}

</script>

<svelte:head>
    <title>Contact</title>
</svelte:head>

<div>
  <h1>Page de contact</h1>
  <p>Ceci est un test de page de contact</p>

  <form on:click|preventDefault={handleSubmitContact}>
    <label for="username">Nom :</label>
    <input type="text" name="username" id="username"/>
    <label for="lastname">Prénom</label>
    <input type="text" name="lastname" id="lastname"/>

    <button>Submit</button>
  </form>
</div>