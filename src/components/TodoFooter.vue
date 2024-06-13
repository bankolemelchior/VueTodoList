<template>
    <footer class="footer">
        <span class="todo-count">
            <strong>10</strong>Tâche retantes
        </span>

        <ul class="filters">
            <li>
                <RouterLink to:="#">Tous</RouterLink>
            </li>
            <li>
                <RouterLink to:="#">En cours</RouterLink>
            </li>
            <li>
                <RouterLink to:="#">Terminé</RouterLink>
            </li>
            <li>
                <RouterLink to:="#">Tous</RouterLink>
            </li>
        </ul>

        <button class="clear-completed">Sup. teminées</button>
    </footer>
</template>

<script setup lang='ts'></script>

<style scoped></style>