<template>
    <div>
        <ul>
            <li v-for="n in 10" :key="n">
                {{n}}
            </li>
        </ul>
    </div>
</template>