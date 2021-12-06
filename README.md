- 👋 Hi, I’m @onedraw
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
onedraw/onedraw is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Deprecated: usort(): Returning bool from comparison function is deprecated, return an integer less than, equal to, or greater than zero in /home/oa9xzzti9d4s/public_html/porngrabbz.com/wp-content/plugins/wp-script-core/wp-script-core.php on line 872
 
		// add products submenus.
		foreach ( (array) $final_nav_elts as $final_nav_elt ) {
			$slug = strtoupper( current( explode( '-', $final_nav_elt['slug'] ) ) );
			if ( 'WPSCORE' === $slug || ( WPSCORE()->php_version_ok() && ( 'WPST' === $slug || 'connected' === WPSCORE()->get_product_status( $slug ) ) ) ) {
				if ( isset( $final_nav_elt['slug'], $final_nav_elt['callback'], $final_nav_elt['title'] ) ) {
					$final_nav_elt['title'] = 'WP-Script' === $final_nav_elt['title'] ? 'Dashboard' : $final_nav_elt['title'];
					add_submenu_page( 'wpscore-dashboard', $final_nav_elt['title'], $final_nav_elt['title'], 'manage_options', $final_nav_elt['slug'], $final_nav_elt['callback'] );
				}
        I cant tell what's wrong here.
