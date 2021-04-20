<template>
    <div>
        <div class="filter-container" style="display: flex; justify-content: space-between">
            <button type="button" style="margin-left: 10px"
             class="el-button filter-item el-button--primary el-button--medium">
                <i class="el-icon-edit"></i>
                <span> 新增视频 </span>
            </button>
            <div style="width: 90px; margin-right: 10px" class="el-select filter-item el-select--medium"          >
                <div class="el-input el-input--medium el-input--suffix">
                    <input type="text" readonly="readonly"
                        autocomplete="off" placeholder="商品状态"  class="el-input__inner"/>
                    <span class="el-input__suffix">
                        <span class="el-input__suffix-inner">
                            <i class="el-select__caret el-input__icon el-icon-arrow-up"></i>
                        </span>
                    </span>
                </div>
            </div>
            <div style="width: 200px" class="filter-item el-input el-input--medium">
                <input autocomplete="off" type="text" placeholder="标题" class="el-input__inner" />
            </div>
            <button type="button" class="el-button filter-item el-button--primary el-button--medium">
                <i class="el-icon-search"></i><span> 搜索 </span>
            </button>
        </div>



        <div data-v-6af373ef="" class="pagination-container" style="">
            <div data-v-6af373ef="" class="el-pagination is-background">
                <span class="el-pagination__total">Total 100</span>
                <span class="el-pagination__sizes">
                    <div class="el-select el-select--mini">
                        <div class="el-input el-input--mini el-input--suffix">
                            <input type="text" readonly="readonly" autocomplete="off" placeholder="Select" class="el-input__inner">
                            <span class="el-input__suffix">
                                <span class="el-input__suffix-inner">
                                    <i class="el-select__caret el-input__icon el-icon-arrow-up"></i>
                                </span>
                            </span>
                        </div>
                    </div>
                </span>
                <button type="button" class="btn-prev">
                    <i class="el-icon el-icon-arrow-left"></i>
                </button>
                <ul class="el-pager">
                    <li class="number">1</li>
                    <li class="number active">2</li>
                    <li class="number">3</li>
                    <li class="number">4</li>
                    <li class="number">5</li>
                    </ul>
                    <button type="button" class="btn-next">
                        <i class="el-icon el-icon-arrow-right"></i>
                    </button>
                    <span class="el-pagination__jump">Go to
                        <div class="el-input el-input--medium el-pagination__editor is-in-pagination">
                            <input type="number" autocomplete="off" min="1" max="5" class="el-input__inner">
                        </div>
                    </span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>