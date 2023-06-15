<script>
    export default {
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
                <li>Home</li>
                <li>About Us</li>
                <li>Products</li>
                <li>Contact Us</li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss">
    
</style>