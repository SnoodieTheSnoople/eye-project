<script>
    import { Button, ButtonGroup, Modal } from "flowbite-svelte";
    let clickOutsideModal = false;
</script>

<Button on:click={() => (clickOutsideModal = true)}>Get Started</Button>

<Modal title="Questionnaire" bind:open={clickOutsideModal} autoclose outsideclose>
    <h1>Are you using a mobile device?</h1>
    <ButtonGroup>
        <Button>Yes</Button>
        <Button>No</Button>
    </ButtonGroup>
</Modal>