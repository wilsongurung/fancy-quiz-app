<template>
    <div class="container">
    <div class="row">
    <div class="col-sm-6 offset-3">
    <b-nav tabs>
        <b-nav-item disabled><strong>Fancy Quiz App</strong></b-nav-item>
        <b-nav-item disabled class="float-right"><strong>Counter: </strong> {{ numCorrect }}/{{ numTotal }}</b-nav-item>
    </b-nav>
    </div>
    </div>
    </div>
</template>

<script>
export default {
    props: [
        'numCorrect',
        'numTotal'
    ]
}
</script>

