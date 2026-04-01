#include <iostream>
#include <cstring>
using namespace std;

const int MAX_LOC = 30;   // 最大地点数
const int MAX_CAT = 10;   // 最大分类数
const int NAME_LEN = 20;  // 名称最大长度

// 分类结构体（线性表元素）
struct Category {
    int id;
    char name[NAME_LEN];
};

// 地点结构体（线性表元素）
struct Location {
    int id;
    char name[NAME_LEN];
    int category_id;  // 所属分类ID
};

// 地点线性表（顺序表）
struct LocationList {
    Location data[MAX_LOC];
    int length;
};

// 分类线性表（顺序表）
struct CategoryList {
    Category data[MAX_CAT];
    int length;
};

// 初始化地点线性表
void initLocList(LocationList &list) {
    list.length = 0;
}

// 初始化分类线性表
void initCatList(CategoryList &list) {
    list.length = 0;
}

// 添加地点
bool addLocation(LocationList &list, int id, const char* name, int catId) {
    if (list.length >= MAX_LOC) return false;
    list.data[list.length].id = id;
    strcpy(list.data[list.length].name, name);
    list.data[list.length].category_id = catId;
    list.length++;
    return true;
}

// 添加分类
bool addCategory(CategoryList &list, int id, const char* name) {
    if (list.length >= MAX_CAT) return false;
    list.data[list.length].id = id;
    strcpy(list.data[list.length].name, name);
    list.length++;
    return true;
}

// 遍历打印所有地点
void printAllLocations(const LocationList &list) {
    cout << "=== 全部校园地点（共" << list.length << "个）===" << endl;
    for (int i = 0; i < list.length; i++) {
        cout << list.data[i].id << ". " << list.data[i].name << endl;
    }
}

// 根据分类ID获取分类名称
const char* getCategoryName(const CategoryList &catList, int catId) {
    for (int i = 0; i < catList.length; i++) {
        if (catList.data[i].id == catId) {
            return catList.data[i].name;
        }
    }
    return "未知分类";
}

// 按分类筛选地点
void filterByCategory(const LocationList &locList, const CategoryList &catList, int catId) {
    cout << "\n=== 分类【" << getCategoryName(catList, catId) << "】下的地点 ===" << endl;
    bool found = false;
    for (int i = 0; i < locList.length; i++) {
        if (locList.data[i].category_id == catId) {
            cout << "- " << locList.data[i].name << endl;
            found = true;
        }
    }
    if (!found) {
        cout << "该分类下暂无地点。" << endl;
    }
}

int main() {
    LocationList locList;
    CategoryList catList;
    initLocList(locList);
    initCatList(catList);

    // 添加预设分类
    addCategory(catList, 1, "教学区");
    addCategory(catList, 2, "生活区");
    addCategory(catList, 3, "运动区");
    addCategory(catList, 4, "校门区");

    // 添加全部21个地点
    // 教学区
    addLocation(locList, 1, "弘义楼西", 1);
    addLocation(locList, 2, "弘义楼", 1);
    addLocation(locList, 3, "弘义楼东", 1);
    addLocation(locList, 4, "明德楼", 1);
    addLocation(locList, 5, "明德楼西", 1);
    addLocation(locList, 6, "明德楼东", 1);
    addLocation(locList, 7, "图书馆", 1);
    addLocation(locList, 8, "致远楼", 1);
    // 生活区
    addLocation(locList, 9, "今日餐厅", 2);
    addLocation(locList, 10, "1A楼", 2);
    addLocation(locList, 11, "1B楼", 2);
    addLocation(locList, 12, "2A楼", 2);
    addLocation(locList, 13, "2B楼", 2);
    addLocation(locList, 14, "3A楼", 2);
    addLocation(locList, 15, "3B楼", 2);
    // 运动区
    addLocation(locList, 16, "体育场", 3);
    addLocation(locList, 17, "球场", 3);
    // 校门区
    addLocation(locList, 18, "综合楼", 4);
    addLocation(locList, 19, "北门", 4);
    addLocation(locList, 20, "北二门", 4);

    // 测试功能
    printAllLocations(locList);
    filterByCategory(locList, catList, 1);  // 查看教学区
    filterByCategory(locList, catList, 2);  // 查看生活区

    return 0;
}
