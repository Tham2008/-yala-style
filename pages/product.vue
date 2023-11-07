<template>
    <Header></Header>
    <main class="">
      <div class="layout-collections">
	<div class="breadcrumb-shop">
  
	<div class="breadcrumb-list mt-[-1px] bg-[#f5f5f5] px-[8px] py-[15px]">
    <div class="container">
		<ol class="breadcrumb flex text-sm py-[9]" itemscope="" itemtype="http://schema.org/BreadcrumbList">
		
			
			
			<li class="active" itemprop="itemListElement" itemscope="" itemtype="http://schema.org/ListItem">
				<span itemprop="item" content="https://yala-style.myharavan.com/collections/all"><strong itemprop="name">Tất cả sản phẩm</strong></span>
				<meta itemprop="position" content="3">
			</li>
			
			
			
		</ol>
	</div>
</div>
</div>

</div>
<!-- hình ảnh -->
<div class="collection-banner-header">
		<img class=" ls-is-cached lazyloaded" data-src="//theme.hstatic.net/200000301562/1000687964/14/collection_banner.jpg?v=3265" src="//theme.hstatic.net/200000301562/1000687964/14/collection_banner.jpg?v=3265" alt="Products">
	</div>
  <!-- wrapper-mainCollection -->
  <div class="wrapper-mainCollection">
    <!--heading -->
    <div class="collection-heading my-[30px]">
			<div class="container">
        <div class="row flex flex-col md:flex-row justify-between items-center">
    <div class="flex-8 md:mr-4">
        <h1 class="text-3xl font-bold">
            Tất cả sản phẩm
        </h1>
    </div>
    <div class="flex-2 mt-4 md:mt-0">
        <div class="collection-sortbyfilter-container">
            <div class="collection-sortby-filter flex relative">
                <div class="collection-sortby flex-1 w-full md:w-1/2">
                    <div class="layered_filter relative h-9 md:h-38  font-semibold pr-40 pt-2 border border-inherit group" @mouseenter="isDropdownVisible = true" @mouseleave="isDropdownVisible = false">
                        <p class="title_filter flex cursor-pointer overflow-hidden">
                          
                            <span >Sắp xếp</span>
                        </p>
                        <ul class="dropdown absolute left-0 top-10 w-full mt-2 px-2 py-1 bg-white border border-inherit opacity-0 group-hover:opacity-100 transition-opacity" v-if="isDropdownVisible">
                            <li><a href="#">Sắp xếp theo tên A-Z</a></li>
                            <li><a href="#">Sắp xếp theo tên Z-A</a></li>
                            <li><a href="#">Sắp xếp theo giá tăng dần</a></li>
                            <li><a href="#">Sắp xếp theo giá giảm dần</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>


			</div>
	</div>
<!-- filter -->

<!-- Sản phẩm -->
<div class="collection-listproduct" id="collection-body">
		
        <section class="mt-10">
		<div class="container">

		<div class="section-content ">
			<div class="grid grid-cols-1 sm:grid-cols-1 ">
        <div class="row">
      <div class="grid grid-cols-2 sm:grid-cols-4">
        <!-- products -->
            <div class="product-inner mx-auto p-2 h-72">
                <div class="proloop-image relative w-">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                    <!-- Sử dụng lớp của Tailwind CSS để điều chỉnh kích thước ảnh -->
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-59_e4227fe53c74486e95c3e1621e590bb2_medium.jpg" src="//product.hstatic.net/200000301562/product/product-59_e4227fe53c74486e95c3e1621e590bb2_medium.jpg" alt=" Sơ Mi Nam Tay Dài ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-58_2327ae8624874ce396a92d90ed9f82b5_medium.jpg" alt=" Sơ Mi Nam Tay Dài " src="//product.hstatic.net/200000301562/product/product-58_2327ae8624874ce396a92d90ed9f82b5_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>
                <a href="/products/ao-co-slogan" class="proloop-link quickview-product" data-handle="/products/ao-co-slogan" title="Áo có slogan"></a>
                <div class="proloop-detail pt-3 ">
                    <h3><a href="/products/ao-co-slogan" class="quickview-product" data-handle="/products/ao-co-slogan">Sơ Mi Nam Tay Dài</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">440,000₫</span>
                        <!-- <span class="price-del text-sm font-light line-through">460,000₫</span> -->
                    </p>
                </div>
            </div>

             <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/am-2_bdbfaa6332744939a95ae473eec398ba_05b1d97767f94ff894c7aaa879a45be9_417ecc54993d4d9da0029a5e3b3b56da_medium.jpg" src="//product.hstatic.net/200000301562/product/am-2_bdbfaa6332744939a95ae473eec398ba_05b1d97767f94ff894c7aaa879a45be9_417ecc54993d4d9da0029a5e3b3b56da_medium.jpg" alt=" Áo Thun Nam Y2010 Basic Z02 ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/-2-2_52d155e2fccb40188b82921d65fbd090_a2c1406d8bba4f43a30bd566199acea1_064db6a3beec48b6a7f16357011476c7_medium.jpg" alt=" Áo Thun Nam Y2010 Basic Z02 " src="//product.hstatic.net/200000301562/product/-2-2_52d155e2fccb40188b82921d65fbd090_a2c1406d8bba4f43a30bd566199acea1_064db6a3beec48b6a7f16357011476c7_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>
                <a href="/products/ao-co-slogan" class="proloop-link quickview-product" data-handle="/products/ao-co-slogan" title="Áo Thun Nam Y2010 Basic Z02"></a>
                <div class="proloop-detail pt-3 ">
                    <h3><a href="/products/ao-co-slogan" class="quickview-product" data-handle="/products/ao-co-slogan">Áo Thun Nam Y2010 Basic Z02</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">150,000₫</span>
                        <span class="price-del text-sm font-light line-through">200,000₫</span>
                    </p>
                </div>
            </div>
        
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-64_78a51e7697b94746a4b643079a13423d_medium.jpg" src="//product.hstatic.net/200000301562/product/product-64_78a51e7697b94746a4b643079a13423d_medium.jpg" alt=" Quần short nam phong cách Hàn Quốc ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/-1-7_14c6ab15348f4d21905eb0800d46fbf6_42accfb3e52b4689b64aa83220846658_682ceb16ad76494f9eaf2fc390bf9e6c_medium.jpg" alt=" Quần short nam phong cách Hàn Quốc " src="//product.hstatic.net/200000301562/product/-1-7_14c6ab15348f4d21905eb0800d46fbf6_42accfb3e52b4689b64aa83220846658_682ceb16ad76494f9eaf2fc390bf9e6c_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>

                <div class="proloop-detail pt-3 ">
                    <h3><a>Quần short nam phong cách Hàn Quốc </a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">200,000₫</span>
                        <span class="price-del text-sm font-light line-through">300,000₫</span>
                    </p>
                </div>
            </div>
        
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

          
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-60_7e69b9a19ff4470a8b6ef4c79b556327_medium.jpg" src="//product.hstatic.net/200000301562/product/product-60_7e69b9a19ff4470a8b6ef4c79b556327_medium.jpg" alt=" Áo khoác thời &quot; trang nam ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-61_20aa466b50ea4f6fb8fac58532f6d064_medium.jpg" alt=" Áo khoác thời &quot; trang nam " src="//product.hstatic.net/200000301562/product/product-61_20aa466b50ea4f6fb8fac58532f6d064_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>
      
                <div class="proloop-detail pt-3 ">
                    <h3><a> Áo khoác thời &quot; trang nam</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">1,100,000₫</span>
                    
                    </p>
                </div>
            </div>
       
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>


                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-57-1_a870f68348f64297be8e09a2ce8316a1_medium.jpg" src="//product.hstatic.net/200000301562/product/product-57-1_a870f68348f64297be8e09a2ce8316a1_medium.jpg" alt=" Áo khoác caro tay dài ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-57_bc37448bd2624d469f2a39ed8f1e9895_medium.jpg" alt=" Áo khoác caro tay dài " src="//product.hstatic.net/200000301562/product/product-57_bc37448bd2624d469f2a39ed8f1e9895_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>
 
                <div class="proloop-detail pt-3 ">
                    <h3><a> Áo khoác caro tay dài</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">345,000₫</span>
                        <!-- <span class="price-del text-sm font-light line-through">460,000₫</span> -->
                    </p>
                </div>
            </div>
  
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                  
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-32_a886407c51de47848f82bcdd050225d7_medium.jpg" src="//product.hstatic.net/200000301562/product/product-32_a886407c51de47848f82bcdd050225d7_medium.jpg" alt=" Áo Sơ Mi Nam Tay Dài ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-33_30fd028023fa477185397fb7f44f66cb_medium.jpg" alt=" Áo Sơ Mi Nam Tay Dài " src="//product.hstatic.net/200000301562/product/product-33_30fd028023fa477185397fb7f44f66cb_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>
               
                <div class="proloop-detail pt-3 ">
                    <h3><a > Áo Sơ Mi Nam Tay Dài</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">500,000₫</span>
                        <span class="price-del text-sm font-light line-through">650,000₫</span>
                    </p>
                </div>
            </div>


            <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                    <!-- Sử dụng lớp của Tailwind CSS để điều chỉnh kích thước ảnh -->
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                                <img class="img-loop ls-is-cached lazyloaded max-w-full h-auto" src="//product.hstatic.net/200000301562/product/product-1_0073697ed8b8462d9384015b2cc77df8_medium.jpg" alt="Áo có slogan">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                                <img class="img-loop ls-is-cached lazyloaded max-w-full h-auto" src="//product.hstatic.net/200000301562/product/product-2_d7a834ee162a475ab700be1f6992ff3c_medium.jpg" alt="Áo có slogan">
                            </div>
                        </div>
                    </div>
                </div>
                <a href="/products/ao-co-slogan" class="proloop-link quickview-product" data-handle="/products/ao-co-slogan" title="Áo có slogan"></a>
                <div class="proloop-detail pt-3 ">
                    <h3><a href="/products/ao-co-slogan" class="quickview-product" data-handle="/products/ao-co-slogan">Áo có slogan</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">360,000₫</span>
                        <span class="price-del text-sm font-light line-through">460,000₫</span>
                    </p>
                </div>
            </div>
            
             <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                   
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-13_d19ba4df7dd34dd9b328deef608609dc_medium.jpg" src="//product.hstatic.net/200000301562/product/product-13_d19ba4df7dd34dd9b328deef608609dc_medium.jpg" alt=" Áo len nữ có slogan ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-14_f6f4f9afa4e549eb9725969c6278a05d_medium.jpg" alt=" Áo len nữ có slogan " src="//product.hstatic.net/200000301562/product/product-14_f6f4f9afa4e549eb9725969c6278a05d_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>

                <div class="proloop-detail pt-3 ">
                    <h3><a>Áo len nữ có slogan </a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">250,000₫</span>
                        <span class="price-del text-sm font-light line-through">290,000₫</span>
                    </p>
                </div>
            </div>
          
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                   
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-5-1_199e50d56a6a410590da2813e0c9b9c2_medium.jpg" src="//product.hstatic.net/200000301562/product/product-5-1_199e50d56a6a410590da2813e0c9b9c2_medium.jpg" alt=" Áo phông đồ họa Jersey ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-5_9cad4f7f330c448791e9ad999c4908ea_medium.jpg" alt=" Áo phông đồ họa Jersey " src="//product.hstatic.net/200000301562/product/product-5_9cad4f7f330c448791e9ad999c4908ea_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>

                <div class="proloop-detail pt-3 ">
                    <h3><a >Áo phông đồ họa Jersey</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">270,000₫</span>
                        <span class="price-del text-sm font-light line-through">490,000₫</span>
                    </p>
                </div>
            </div>
          
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                    
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-11_1cb5101e9314460cbd47c04148da3c92_medium.jpg" src="//product.hstatic.net/200000301562/product/product-11_1cb5101e9314460cbd47c04148da3c92_medium.jpg" alt=" Áo len cổ tròn kiểu Cổ điển ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-4_09543445dfc1436dbeb9469a52ff06e9_medium.jpg" alt=" Áo len cổ tròn kiểu Cổ điển " src="//product.hstatic.net/200000301562/product/product-4_09543445dfc1436dbeb9469a52ff06e9_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>

                <div class="proloop-detail pt-3 ">
                    <h3><a >Áo len cổ tròn kiểu Cổ điển</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">240,000₫</span>
                        <span class="price-del text-sm font-light line-through">270,000₫</span>
                    </p>
                </div>
            </div>
              <!-- Lặp qua danh sách sản phẩm -->
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                    <!-- Sử dụng lớp của Tailwind CSS để điều chỉnh kích thước ảnh -->
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                              <img class="img-loop ls-is-cached lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-3_f178a012a08744a8b93232bc873867d0_medium.jpg" src="//product.hstatic.net/200000301562/product/product-3_f178a012a08744a8b93232bc873867d0_medium.jpg" alt=" Áo len thời trang kiểu Hàn ">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                              <img class="img-loop lazyloaded" data-src="//product.hstatic.net/200000301562/product/product-6_c414a44d7b694dabbbfc2744b0fe4dc7_medium.jpg" alt=" Áo len thời trang kiểu Hàn " src="//product.hstatic.net/200000301562/product/product-6_c414a44d7b694dabbbfc2744b0fe4dc7_medium.jpg">
                            </div>
                        </div>
                    </div>
                </div>
          
                <div class="proloop-detail pt-3 ">
                    <h3><a >Áo len thời trang kiểu Hàn</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">670,000₫</span>
                        <span class="price-del text-sm font-light line-through">700,000₫</span>
                    </p>
                </div>
            </div>
              <!-- Lặp qua danh sách sản phẩm -->
              <div class="product-inner mx-auto p-2">
                <div class="proloop-image relative">
                    <div class="pro-sale absolute left-1 bg-[#e95959] z-10 top-1 text-xs font-medium px-[5px] py-[2px] text-white"><span>-22%</span></div>

                    <!-- Sử dụng lớp của Tailwind CSS để điều chỉnh kích thước ảnh -->
                    <div class="product--image relative text-center">
                        <div class="product-image-container">
                            <!-- Ảnh gốc -->
                            <div class="prod-img first-image flex">
                                <img class="img-loop ls-is-cached lazyloaded max-w-full h-auto" src="//product.hstatic.net/200000301562/product/product-1_0073697ed8b8462d9384015b2cc77df8_medium.jpg" alt="Áo có slogan">
                            </div>
                            <!-- Ảnh thay thế khi hover -->
                            <div class="prod-img second-image hovered">
                                <img class="img-loop ls-is-cached lazyloaded max-w-full h-auto" src="//product.hstatic.net/200000301562/product/product-2_d7a834ee162a475ab700be1f6992ff3c_medium.jpg" alt="Áo có slogan">
                            </div>
                        </div>
                    </div>
                </div>
                <a href="/products/ao-co-slogan" class="proloop-link quickview-product" data-handle="/products/ao-co-slogan" title="Áo có slogan"></a>
                <div class="proloop-detail pt-3 ">
                    <h3><a href="/products/ao-co-slogan" class="quickview-product" data-handle="/products/ao-co-slogan">Áo có slogan</a></h3>
                    <p class="proloop--price">
                        <span class="price text-sm font-semibold mr-4">360,000₫</span>
                        <span class="price-del text-sm font-light line-through">460,000₫</span>
                    </p>
                </div>
            </div>
        </div>
        
    </div>
         
    
				</div>
</div>

   
</div>



		</section>
			</div>
		</div>

    </main>
    <Footer></Footer>
</template>
<script>
export default {
  data() {
    return {
      isDropdownVisible: false,
	  isBrandDropdownVisible: false,
      isPriceDropdownVisible: false
    };
  },
  methods: {
    toggleDropdown() {
      this.isDropdownVisible = !this.isDropdownVisible;
    },
	toggleBrandDropdown() {
      this.isBrandDropdownVisible = !this.isBrandDropdownVisible;
    },
    togglePriceDropdown() {
      this.isPriceDropdownVisible = !this.isPriceDropdownVisible;
    }
  },
};

</script>
