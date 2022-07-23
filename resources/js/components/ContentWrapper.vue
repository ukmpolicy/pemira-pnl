<template>
    <!-- Content Wrapper -->
    <div id="content-wrapper" class="d-flex flex-column">

        <!-- Main Content -->
        <div id="content">

            <Topbar/>
            <Content/>

        </div>
        <!-- End of Main Content -->

        <!-- Footer -->
        <footer class="sticky-footer bg-white">
            <div class="container my-auto">
                <div class="copyright text-center my-auto">
                    <span>Copyright &copy; Your Website 2020</span>
                    <div class="small text-black" style="font-size: 12px;">Copyright &copy;2021 KIP-PNL. Developed by <a href="www.ukmpolicy.org">UKM-POLICY</a>.</div>
                </div>
            </div>
        </footer>
        <!-- End of Footer -->

    </div>
    <!-- End of Content Wrapper -->
</template>

<script>
import Content from './Content.vue';
import Topbar from './Topbar.vue';

export default {
    components: {
        Topbar, Content
    }
}
</script>