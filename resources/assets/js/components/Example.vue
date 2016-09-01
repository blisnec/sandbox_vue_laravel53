<template>
    <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <div class="panel panel-default">
                    <div class="panel-heading">Example Component</div>

                    <div class="panel-body">
                        {{ message }}
                        <input v-model="message">
                        <pre>
                            {{ $data | json }}
                        </pre>
                        <picture></picture>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import Picture from './Picture.vue';
    export default {
        data () {
            return {
                message: 'I\'m an example component!'
            };
        },
        components: { Picture }
    }
</script>
