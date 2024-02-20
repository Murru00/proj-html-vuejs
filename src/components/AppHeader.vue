<script>
import { store } from '../store/index';

export default {
    data() {
        return {
            links: [
                {
                    link: 'Home',
                },
                {
                    link: 'Landing',
                },
                {
                    link: 'Pages',
                }, 
                {
                    link: 'Docs',
                }


            ],
            icons: [
                {
                    iconName: 'fa-brands fa-github'
                },
                {
                    iconName: 'fa-solid fa-book-open'
                },
                {
                    iconName: 'fa-regular fa-user'
                }
            ],
            store,
        };
    }
};
</script>