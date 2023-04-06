<template>
    <div>
        <div class="row" >
            <div class="col">
                <h5><i class="bi-clipboard-check me-2"></i>Equipes Montadas</h5>
            </div>
        </div>
        <div class="row">
            <div class="col">
                <ListaEquipes />
            </div>
        </div>
    </div>
</template>

<script>
import ListaEquipes from '@/components/ListaEquipes'

export default {
    name: 'Equipes',
    components: {
        ListaEquipes
    }
}
</script>