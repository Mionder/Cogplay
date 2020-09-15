<template>
    <div class="pricing">
        <div class="pricing_title-block">
            <div class="_container"> 
                <div class="pricing_title-block_wrapper">
                    <img src="../assets/Pricing/logo.png" alt="logo" class="logo">
                    <h3 class="pricing_title">Find the perfect plan for you</h3>
                    <p class="pricing_subtitle">Simple pricing that works at any scale</p>
                </div>
            </div>
        </div>
        <div class="pricing_plan-block">
            <div class="_container">
                <div class="pricing_plan-block_wrapper">
                    <div class="pricing_card-item">
                        <img src="../assets/Pricing/parents.png" class="pricing_card-price" alt="parents-price">
                        <p class="price_card-title">Parents</p>
                        <p class="price_card-subtitle">Parents with 1 child</p>
                        <button class="price_card-button">Become a member</button>
                    </div>
                    <div class="pricing_card-item">
                        <img src="../assets/Pricing/teachers.png" class="pricing_card-price" alt="teachers-price">
                        <p class="price_card-title">Teachers</p>
                        <p class="price_card-subtitle">Teacher with 30 children</p>
                        <button class="price_card-button">Become a member</button>
                    </div>
                    <div class="pricing_card-item">
                        <img src="../assets/Pricing/schools.png" class="pricing_card-price" alt="schools-price">
                        <p class="price_card-title">Schools</p>
                        <p class="price_card-subtitle">4 Teachers and 120 students</p>
                        <button class="price_card-button">Become a member</button>
                    </div>
                </div>
            </div>
        </div>      
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.pricing{
    margin-bottom: -75px;
}
.pricing_title-block{
    background-color: #1312DD;
    min-height: 474px;
    ._container {
        max-width: 1266px;
        margin: 0 auto;
        .pricing_title-block_wrapper{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            padding-top: 38px;
            .logo{
                width: 88px;
                height: 49px;
            }
            .pricing_title{
                font-weight: 400;
                font-size: 40px;
                line-height: 60px;
                color: #FFFFFF;
            }
            .pricing_subtitle{
                font-weight: normal;
                font-size: 20px;
                line-height: 30px;
                color: #FFFFFF;
            }
        }
    }
}
.pricing_plan-block{
    transform: translateY(-135px);
    .pricing_plan-block_wrapper{
        display: flex;
        justify-content: space-between;
        .pricing_card-item{
            padding: 50px 0;
            display: flex;
            align-items: center;
            flex-direction: column;
            background: #FFFFFF;
            box-shadow: 0px 4px 14px rgba(19, 15, 64, 0.4);
            border-radius: 10px;
            max-width: 402px;
            width: 100%;
            .pricing_card-price{
                max-width: 253px;
                height: auto;
            }
            .price_card-title{
                margin-top: 30px;
                font-weight: 600;
                font-size: 30px;
                line-height: 45px;
                text-align: center;
                color: #130F40;
            }
            .price_card-subtitle{
                font-weight: 300;
                font-size: 20px;
                line-height: 30px;
                text-align: center;
                color: #2C2C2C;
                margin-bottom: 20px;
            }
            .price_card-button{
                padding: 11px 42px;                              
                background: #F6EF25;
                border-radius: 100px;
                font-weight: 300;
                font-size: 14px;
                line-height: 21px;
                color: #232323;
                border: none;
                cursor: pointer;
            }
        }
    }
}



</style>