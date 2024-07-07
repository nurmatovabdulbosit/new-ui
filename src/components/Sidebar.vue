<template>
   <input type="checkbox" id="menu-toggle">
    <div class="sidebar">
        <div class="side-header">
            <h3>I<span>vest</span></h3>
        </div>
        
        <div class="side-content">
            <div class="profile">
                <div class="profile-img bg-img" style="background-image: url(/src/assets/customer01.jpg)"></div>
                <h4>Abdulbosit</h4>
                <small>Invest Progrem</small>
            </div>
		<div class="side-menu">
			<ul>
				<li>
						<router-link to="/" class="active">
							<span class="las la-home"></span>
							<small>Bosh sahifa</small>
						</router-link>
				</li>
				<li>
					
						<router-link to="/gip" class="active">
						<span class="las la-user-alt"></span>
						<small>Horijiy investitsiya (GIP)</small>
						</router-link>
					
				</li>
				<li>
					
						<router-link to="/rip" class="active">
							<span class="las la-envelope"></span>
							<small>Hududiy investitsiya (RIP)</small>
						</router-link>
					
				</li>

			</ul>
		</div>
	</div>
</div>
	
	
	

		
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>