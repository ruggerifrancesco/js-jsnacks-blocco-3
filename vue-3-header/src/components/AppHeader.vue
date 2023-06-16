<script>
import NavLink from './NavLink.vue';

    export default {
        components: {
            NavLink
        },
        data() {
            return {
                navItemLinks: [
                    {
                        link: '#',
                        idItem: 1,
                        itemName: 'Home',
                    },
                    {
                        link: '#',
                        idItem: 2,
                        itemName: 'About Us',
                    },
                    {
                        link: '#',
                        idItem: 3,
                        itemName: 'Products',
                    },
                    {
                        link: '#',
                        idItem: 4,
                        itemName: 'Contact Us',
                    },
                ],
            }
        },
    }
</script>

<template>
    <header>
        <nav>
            <ul>
                <NavLink v-for="item in navItemLinks"
                :item-name="item.itemName"/>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
    ul {
        display: flex;
        list-style: none;
        gap: 2rem;
    }
</style>