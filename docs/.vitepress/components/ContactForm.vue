<script>
export default {}
</script>

<template>
  <form name="contact" method="POST" data-netlify="true">
    <p>
      <label>Your Name: <input type="text" name="name" /></label>
    </p>
    <p>
      <label>Your Email: <input type="email" name="email" /></label>
    </p>
    <p>
      <label
        >Ice Cream or Gelato?
        <select name="role[]" multiple>
          <option value="ice-cream">Ice Cream</option>
          <option value="gelato">gelato</option>
        </select></label
      >
    </p>
    <p>
      <label>Message: <textarea name="message"></textarea></label>
    </p>
    <p>Test Button Text <button type="submit">Send</button></p>
    <p>Hello more text after the button</p>
    <button>New Submit</button>
  </form>
</template>

<style></style>
