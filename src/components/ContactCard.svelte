<script>
    let {name} = $props()
</script>

<div class="contact-card">
    <img src={imageLink} alt={name} class="contact-image" />
    <h3 class="contact-name">{name}</h3>
    <p class="contact-description">{description}</p>
</div>

<style>
    .contact-card {
        border: 2px solid #ccc;
        border-radius: 8px;
        padding: 16px;
        text-align: center;
        max-width: 300px;
        margin: 16px;
    }
    .contact-image {
        width: 100%;
        height: auto;
        border-radius: 8px;
    }
    .contact-name {
        font-size: 1.5em;
        margin: 8px 0;
    }
    .contact-description {
        font-size: 1em;
        color: #666;
    }
</style>