<template>
    <div class="home">
        <mu-appbar style="width: 100%; margin-bottom: auto;">
            Fabblink
            <mu-button flat slot="right">LOGIN</mu-button>
        </mu-appbar>
        <main class="content">...</main>

        <mu-container class="footer">
            <mu-bottom-nav>
                <mu-bottom-nav-item title="Search Model" icon="3d_rotation"></mu-bottom-nav-item>
                <mu-bottom-nav-item title="Buy 3D Model" icon="account_balance_wallet"></mu-bottom-nav-item>
                <mu-bottom-nav-item title="License 3D Model" icon="cloud_upload"></mu-bottom-nav-item>
                <mu-bottom-nav-item title="3D Printer" icon="location_on"></mu-bottom-nav-item>
            </mu-bottom-nav>
        </mu-container>
    </div>
</template>

<script>
    export default {
        name: 'Home',
        components: {

        }
    }
</script>

<style lang="scss">
    .home {
        display: flex;
        flex-direction: column;
        min-height: 100vh;
        .content {
            flex:1;
        }
        .footer {

        }
    }
    .mu-appbar-title {
        text-align: left;
        font-weight: bold;
        letter-spacing: -1px;
    }
</style>
